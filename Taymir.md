flowchart LR
    far_far_away[Far Far Away]
    cargopocalypse_pt_2[Cargopocalypse, pt.2]
    cargopocalypse[Cargopocalypse]
    order_master_supreme[Order Master Supreme]
    timber[Timber!]
    port_polar_base_supply[Port Polar Base Supply]
    its_a_long_way_to_the_top[It's A Long Way To The Top]
    village_delivery[Village Delivery]
    on_the_top_of_the_world[On The Top Of The World]
    mountain_maze[Mountain Maze]
    airdrome_logging[Airdrome Logging]
    town_supplies[Town Supplies]
    valley_polar_base_research[Valley Polar Base Research]
    oil_barrels_delivery[Oil Barrels Delivery]
    
    service_hub_reactivation[Service Hub Reactivation]
    cargo_delivery[Cargo Delivery]
    drilling_supplies[Drilling Supplies]
    lumber_mill_supplies[Lumber Mill Supplies]
    supply_crates[Supply Crates]
    drilling_stuff_delivery[Drilling Stuff Delivery]

    pipeline_construction[Pipeline Construction]
    pipeline_repair[Pipeline Repair]
    drilling_parts_delivery[Drilling Parts Delivery]
    oil_delivery[Oil Delivery]
    mountain_delivery[Mountain Delivery]
    floating_drill[Flaoting Drill]
    fire_in_a_barrel[Fire In A Barrel]
    more_parts[More Parts]
    drilling_equipment[Drilling Equipment]
    mountain_pipeline_building[Mountain Pipeline Building]
    drill_rig_dissasembly[Drill Rig Dissasembly]
    from_water_to_the_land[From Water To The Land]
    valley_pipeline_building[Valley Pipeline Building]
    drill_dissasembly[Drill Dissasembly]

    discover_pedro_bay[Discover Pedro Bay]
    discover_mountain_river[Discover Mountain River]
    discover_white_valley[Discover White Valley]

    discover_pedro_bay --> far_far_away
    cargopocalypse --> cargopocalypse_pt_2
    cargo_delivery --> cargopocalypse
    cargo_delivery --> order_master_supreme
    pipeline_construction --> timber
    pipeline_construction --> port_polar_base_supply
    lumber_mill_supplies --> its_a_long_way_to_the_top
    discover_mountain_river --> village_delivery
    discover_mountain_river --> on_the_top_of_the_world
    discover_mountain_river --> mountain_maze
    drilling_equipment --> airdrome_logging
    discover_white_valley --> town_supplies
    discover_white_valley --> valley_polar_base_research
    drilling_equipment --> oil_barrels_delivery

    discover_pedro_bay --> service_hub_reactivation
    pipeline_repair --> cargo_delivery
    service_hub_reactivation --> cargo_delivery
    pipeline_construction --> drilling_supplies
    mountain_delivery --> lumber_mill_supplies
    drilling_equipment --> supply_crates
    drilling_equipment --> drilling_stuff_delivery

    discover_pedro_bay --> pipeline_repair
    pipeline_construction --> drilling_parts_delivery
    pipeline_construction --> oil_delivery
    pipeline_construction --> mountain_delivery
    floating_drill --> mountain_delivery
    pipeline_construction --> floating_drill
    pipeline_construction --> fire_in_a_barrel
    mountain_delivery --> more_parts
    mountain_pipeline_building --> drilling_equipment
    mountain_delivery --> mountain_pipeline_building
    mountain_delivery --> drill_rig_dissasembly
    drilling_equipment --> from_water_to_the_land
    drilling_equipment --> valley_pipeline_building
    drilling_equipment --> drill_dissasembly
