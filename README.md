# From Battlefields to MoMA Exhibitions: Cataloging 1929-2024 Exhibition History Unveiling War Stories

How did MoMA illustrate WWI, WWII, and other wars through exhibitions?

This project leverages MoMA’s Open Exhibition Index Dataset to curate a catalog featuring twenty exhibition items  span-ning ninety five years of the institution’s history, all centered around the theme of "War". Today we are marked by per-sistent news of conflicts and warfare around the world. Del-ving into how contemporary art has grappled with these issues provides a unique avenue for reflection and a meaningful di-alogue about the way forward for us.

Step 1. 
Used Beautiful Soup for web scrapping to extract data from MoMA’s exhibition history website, focusing on the period from 1990 to 2024. Merged this web-scrapped data with MoMA’s Open Exhibition Index Data file covering 1929 to 1989, creating a unified CSV file dataset.

Step 2.
Implemented a Python script to iterate through the exhibition history dataset containing 5,457 items, filtered for exhibitions with titles containing "War" or "Battle". Ensured the printed output is refined, excluding redundant or irrelevant results (e.g., "Andy Warhol").

Step 3.
From a pool of 5,457 items, total of 36 exhibition items were printed. Out of these, 20 selected exhibition items were meticulously cataloged using Omeka-S, an open-source web-publishing platform to create a public digital exhibition. 20 items were bulk-uploaded as a csv file, that was created by python script.

Step 4.
Each item underwent a thorough cataloging process adhering to metadata standards like the Dublin Core Standard and CIDOC CRM Ontology. Also controlled vocabulary such as wikidata Q number and Getty ULAN was used. A dedicated digital exhibition website has been launched to showcase the curated collection. Please visit: http://omekas.prattsi.org/s/moma-war-exhibitions/page/moma-war-exhibitions-about 


