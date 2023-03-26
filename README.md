# london_boundary_gpkg
gpkg layers for London, UK in one place

## direct read into R using SF

Basic Command Units

met_bcu <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/met_police_boundaries.gpkg", layer = "mps_bcus")

Boroughs

met_bocu <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/met_police_boundaries.gpkg", layer = "mps_bocus")

Metropolitan Police Service

met_force <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/met_police_boundaries.gpkg", layer = "mps_force")

Lower Super Output Area 2021

lsoa21 <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/census21_boundary_files.gpkg", layer = "lb_lsoa21")

Middle Super Output Area 2021

msoa21 <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/census21_boundary_files.gpkg", layer = "lb_msoa21")

Census Output Area 2021

coa21 <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/census21_boundary_files.gpkg", layer = "lb_oa21")


