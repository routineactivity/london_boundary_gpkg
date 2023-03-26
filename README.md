# london_boundary_gpkg
gpkg layers for London, UK in one place

## direct read into R using SF

Basic Command Units
met_bcu <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/met_police_boundaries.gpkg", layer = "mps_bcus")

Boroughs
met_bocu <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/met_police_boundaries.gpkg", layer = "mps_bocus")

Metropolitan Police Service
met_force <- st_read("https://github.com/routineactivity/london_boundary_gpkg/raw/main/met_police_boundaries.gpkg", layer = "mps_force")


