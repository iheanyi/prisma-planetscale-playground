# prisma-planetscale-playground

This is a quick application for getting up and running with Prisma and PlanetScale.

### Rough Installation Notes

* `npm install`
* Create a `prisma-playground` database using `pscale db create prisma-playground`
* Create two branches, `initial-setup` and `shadow`...`pscale branch create prisma-playground initial-setup` and `pscale branch create prisma-playground shadow`.
* Connect to these two branches by doing the following: `pscale connect prisma-playground initial-setup` and `pscale connect prisma-playground shadow`.
* Run Prisma commands, create deploy request, etc.
* For a longer walkthrough check out the [docs on PlanetScale](https://docs.planetscale.com/tutorials/automatic-prisma-migrations)
