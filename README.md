# london_boundary_gpkg
gpkg layers for London, UK in one place

## direct read into R using SF

**Basic Command Units**

met_bcu <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/met_police_boundaries.gpkg", layer = "mps_bcus")

**Boroughs**

met_bocu <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/met_police_boundaries.gpkg", layer = "mps_bocus")

**Metropolitan Police Service**

met_force <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/met_police_boundaries.gpkg", layer = "mps_force")

**Lower Super Output Area 2021**

lsoa21 <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/census21_boundary_files.gpkg", layer = "lb_lsoa21")

**Middle Super Output Area 2021**

msoa21 <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/census21_boundary_files.gpkg", layer = "lb_msoa21")

**Census Output Area 2021**

coa21 <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/census21_boundary_files.gpkg", layer = "lb_oa21")

**GLA High Streets**

gla_hs <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/gla_boundary_files.gpkg", layer = "gla_high_streets")

**GLA Town Centres**

gla_tc <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/gla_boundary_files.gpkg", layer = "gla_towncentres")

**GLA Local Industrial Sites**

gla_lis <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/gla_boundary_files.gpkg", layer = "gla_local_industry_sites")

**GLA Strategic Industrial Sites**

gla_sis <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/gla_boundary_files.gpkg", layer = "gla_strategic_industrial")

**GLA Housing Allocations**

gla_ha <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/gla_boundary_files.gpkg", layer = "gla_site_allocations")
