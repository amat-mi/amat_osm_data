# amat_osm_data

**AMAT/OSM data integration project for Milan municipality**

For now this repository is mainly used as reporting tool for the issues on road graph integration.

## (Geo)Issue tracking system

We rely on GitHub issues for signaling that something is wrond with AMAT graph, OSM graph or both.

Just click on "Issues" and create a new issue. The issue body can be organized as a bulleted list with a brief description followed by the map url.

The map url can be generated in JOSM by double-clicking in the lower left corner of the map window (toolbar).

A couple of **labels** have been added for categorizing the issues:

* AMAT graph errors: the AMAT graph is wrong and must be replaced by OSM. Usually, OSM ways should get a loc_ref=-1 in this case.
* In doubt AMAT/OSM: OSM and AMAT graphs are discordant, and there's no way to understand which one is right from the base data we have.
* Insufficient data: we don't have enough information on the area we are working in.

The labels can be used in combination also.

See an example: https://github.com/amat-mi/amat_osm_data/issues/1

Issues can be referenced from one another using #issue_number.

A single issue should be a task which can be completed in half an hour. Please avoid cramming too much problems in the same task. If necessary, split complex tasks into groups or simpler tasks, which can be linked using #task_number.

