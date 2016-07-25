# uw-pokestops
[Pokestop visualization](https://karlding.github.io/uw-pokestops/) on UW campus.

I scraped the Ingress live status map for the region on campus (which included locations that aren't Pokestops), and cleaned up the data to remove points off the top of my head.

If there's mistakes, feel free to submit a pull request for the [CSV](https://github.com/karlding/uw-pokestops/blob/master/data/pokestops.csv), and (eventually) I'll set up Continuous Integration or something so that changes get automatically pulled and a new GeoJSON file is generated in the ``gh-pages`` branch.
