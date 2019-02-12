# diy-prusa-i3-mk3-bear
My attempt to build a Prusa i3 MK3 3D Printer with Full Bear frame from scratch

## Bill of Materials
Assembly/Component Type            | Description                       | Quantity | Possible sources and notes 
---------------------------------- | --------------------------------- | -------- | --------------------------
Full Bear MK3 - Frame and hardware | Full Bear MK3 Upgrade Kit<br>Refer to the detailed BOM [here](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/manual/bom.md) | 1 | ALL3D Makers [MK3 Bear Upgrade](https://all3dmakers.com/collections/bear-upgrade-kit/products/mk3-bear-upgrade)
Full Bear MK3 - 3D Printed parts   | [build_helper_106mm](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/build_helper_106mm.stl) | 1 | Print (priority 1)
Full Bear MK3 - 3D Printed parts   | [rod_holder](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rod_holder.stl) | 4 | Print (priority 1)
Full Bear MK3 - 3D Printed parts   | [y_idler_23](https://www.thingiverse.com/thing:3309424) | 1 | Print (priority 1). Note: 5 mm bore version for E3D 2GT 20T idler
Full Bear MK3 - 3D Printed parts   | [y_motor_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/y_motor_mount.stl) | 1 | Print (priority 1)
Full Bear MK3 - 3D Printed parts   | [z_motor_mounts](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/z_motor_mounts.stl) | 1 (total of 2 parts) | Print (priority 1)
Full Bear MK3 - 3D Printed parts   | [z_motor_mount_front](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/z_motor_mount_front.stl) | 2        | Print (priority 1)
Full Bear MK3 - 3D Printed parts   | [z_tops](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/z_tops.stl) | 1 (total of 2 parts) | Print (priority 1)
Full Bear MK3 - 3D Printed parts   | [foot](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/foot.stl) 4 | Print (priority 2)
Full Bear MK3 - 3D Printed parts   | [psu_lower_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/psu_lower_mount.stl) | 1 | Print (priority 2)
Full Bear MK3 - 3D Printed parts   | [psu_upper_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/psu_upper_mount.stl) | 2 | Print (priority 2)
Full Bear MK3 - 3D Printed parts   | [rambo_base_lower_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_base_lower_mount.stl) | 1 | Print (priority 3)
Full Bear MK3 - 3D Printed parts   | [rambo_base_upper_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_base_upper_mount.stl) | 1 | Print (priority 3)
Full Bear MK3 - 3D Printed parts   | [rambo_lid_lower_hinge](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_lid_lower_hinge.stl) | 1 | Print (priority 3)
Full Bear MK3 - 3D Printed parts   | [rambo_lid_upper_hinge](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_lid_upper_hinge.stl) | 1 | Print (priority 3)
Full Bear MK3 - 3D Printed parts   | [lcd_support_a](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/lcd_support_a.stl) | 1 | Print (priority 3)
Full Bear MK3 - 3D Printed parts   | [lcd_support_b](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/lcd_support_b.stl) | 1 | Print (priority 3)
Full Bear MK3 - 3D Printed parts   | [cable_clip_lcd](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/cable_clip_lcd.stl) | 6 | Print (priority 3)
Full Bear MK3 - 3D Printed parts   | [cable_clip_round](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/cable_clip_round.stl) | 5 | Print (priority 3)
Full Bear MK3 - 3D Printed parts   | [cable_clip_ziptie](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/cable_clip_ziptie.stl) | 3 | Print (priority 3)
Full Bear MK3 - 3D Printed parts   | [end_caps](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/end_caps.stl) | 2 (total of 4 parts) | Print (priority 3)
Full Bear MK3 - 3D Printed parts   | [end_cap_z_axis](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/end_cap_z_axis.stl) | 2 | Print (priority 3)
Bear Extruder and X Axis - MK3     | [x_carriage](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/mk3/x_carriage.stl) | 1 | Print (priority 1)
Bear Extruder and X Axis - MK3     | [x_end_idler](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/common_to_all_versions/x_end_idler.stl) | 1 | Print (priority 1)
Bear Extruder and X Axis - MK3     | [x_end_idler_idler_mount](https://www.thingiverse.com/thing:3308226/files) | 1 | Print (priority 1). Note: 5 mm bore version for E3D 2GT 20T idler
Bear Extruder and X Axis - MK3     | [cable_guide_back_a](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/common_to_all_versions/cable_guide_back_a.stl) | 1 | Print (Priority 3?). Note: Check if needed for Bondtech extruder?
Bear Extruder and X Axis - MK3     | [cable_guide_back_b](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/common_to_all_versions/cable_guide_back_b.stl) | 1 | Print (Priority 3?). Note: Check if needed for Bondtech extruder?
Bear Extruder and X Axis - MK3     | [bondtech_x_carriage_mk3](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/optional_parts/bondtech_x_carriage/printed_parts/bondtech_x_carriage_mk3.stl) | 1 | Print (priority 1)
Bear Extruder and X Axis - MK3     | [x_carriage_back] (https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/mk3/x_carriage_back.stl) | 1 | Print (priority 1)
Original Prusa i3 MK3              | [y-belt-holder](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3/Printed-Parts/stl/y-belt-holder.stl) | 1 | Print (priority 1)
Original Prusa i3 MK3              | [Einsy case; Cable clips](https://github.com/prusa3d/Original-Prusa-i3/tree/MK3/Printed-Parts/stl) | 1 | Print (priority 3). Note: Use a [Bear alternative](https://www.thingiverse.com/thing:3239428)
Original Prusa i3 MK3              | [LCD cover; LCD knob](https://github.com/prusa3d/Original-Prusa-i3/tree/MK3/Printed-Parts/stl) | 1 | Print (priority 3). Note: Use a Bear alternative: [This](https://www.thingiverse.com/thing:3385560) or [this](https://www.thingiverse.com/thing:2941711)
Original Prusa i3 MK3              | [Heatbed cable cover](https://github.com/prusa3d/Original-Prusa-i3/tree/MK3/Printed-Parts/stl) | 1 | Print (priority 3)
LMU8 Linear Bearing                | LMU8 Linear Bearing               | 10       | Misumi [LMU8](https://us.misumi-ec.com/vona2/detail/110300026540/?ProductCode=LMU8)
Metal Rod                          | Z-Axis Rod - 8 mm, 320 mm length  | 2        | Misumi [PSFJ8-320](https://us.misumi-ec.com/vona2/detail/110302634310/?ProductCode=PSFJ8-320)
Metal Rod                          | Y-Axis Rod - 8 mm, 330 mm length  | 2        | Misumi [PSFJ8-330](https://us.misumi-ec.com/vona2/detail/110302634310/?ProductCode=PSFJ8-330)
Metal Rod                          | Z-Axis Rod -                      | 2        | Misumi [PSFJ8-370](https://us.misumi-ec.com/vona2/detail/110302634310/?ProductCode=PSFJ8-370)
2GT Belt                           | 2GT Belt                          | 2        | Misumi [GBN8522GT-60](https://us.misumi-ec.com/vona2/detail/110302652060/?ProductCode=GBN8522GT-60)
2GT 20T Idler                      | 2GT 20 Tooth Idler, 5 mm bore     | 2        | E3D
2GT 16T Pulley                     | 2GT 16 Tooth Pulley, 5 mm bore    | 2        | E3D
Dowel Pin                          | Dowel Pin 24 mm length, 5mm diameter | 1 | Fastenal
Dowel Pin                          | Dowel Pin 15.8 mm length, 5mm diameter | 1 | All3D Makers [Bear X Axis Dowel Pin for E3D Gates 5mm bore idler](https://all3dmakers.com/collections/hardware/products/bear-x-axis-dowel-pin-for-e3d-gates-5mm-bore-idler)
Electronics                        | Einsy Rambo 1.1                   | 1        | UltiMachine [EINSY RAMBo 1.1](https://ultimachine.com/collections/electronics/products/einsy-rambo-1-1)
Electronics                        | 2004 LCD Display - [RepRapDiscount Smart Controller](https://reprap.org/wiki/RepRapDiscount_Smart_Controller) | 1 | eBay
Electronics                        | Filament fan | 1 | All3D Makers
Electronics                        | Hot end fan | 1| Mouser
Electronics                        | Cable / pig tail for hot end fan | 1 | All3D Makers
Electronics                        | PINDA 2 sensor | 1 | All3D Makers
Electronics                        | Filament sensor | 1 | eBay?!
Electronics                        | MK52 headbed | 1 | All3D Makers
Electronics                        | MK3 24V Power Supply | 1 | All3D Makers
Y Carriage                         | Prusa i3 MK3 Aluminum Y carriage | 1 | All3D Makers [Prusa i3 MK3 Aluminum Y carriage](https://all3dmakers.com/collections/hardware/products/original-prusa-i3-mk3-3d-printer-aluminum-y-carriage?variant=14666953883763)
Spring Steel Sheet                 | MK3 Spring Steel Sheet | 1 | BuildTak [FlexPlate MK3 - 9.5"x10"](https://www.buildtak.com/product/flexplate-surface/)
Print Surface                      | Print Surface | 1 | BuiltTak [Original 3ED Printing Surface - 9"X10"](https://www.buildtak.com/product/buildtak-3d-printing-surface/)
Hardware                           | U-Bolts for LMU8U Bearings and nyloc nuts | 1 set | All3D Makers [U-Bolts for LMU8U Bearings](https://all3dmakers.com/collections/hardware/products/u-bolts-to-hold-the-lm8uu-bearings-to-the-y-carriage-on-the-mk2s)


Parts to add to the BOM:
* Motors
* X Axis:
  * Print head:
    * Extruder
    * Hot end
* screws
* nuts


