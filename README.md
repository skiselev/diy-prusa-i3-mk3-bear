# diy-prusa-i3-mk3-bear
My attempt to build an improved Prusa i3 MK3 3D printer clone with Full Bear frame from scratch

## Bill of Materials
Assembly/Component Type     | Description                       | Quantity | Price | Possible sources and notes
----------------------------| --------------------------------- | -------- | ----- | -------------------------- 
Aluminum Frame and Hardware | Full Bear MK3 Upgrade Kit - [Detailed BOM](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/manual/bom.md) | 1 | $124.99 |ALL3D Makers [MK3 Bear Upgrade](https://all3dmakers.com/collections/bear-upgrade-kit/products/mk3-bear-upgrade)
3D Printed Part             | Full Bear MK3 - [build_helper_106mm](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/build_helper_106mm.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [rod_holder](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rod_holder.stl) | 4 | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [y_idler_23](https://www.thingiverse.com/thing:3309424) | 1 | Filament | Print (priority 1). Note: 5 mm bore version for E3D 2GT 20T idler
3D Printed Part             | Full Bear MK3 - [y_motor_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/y_motor_mount.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [z_motor_mounts](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/z_motor_mounts.stl) | 1 (total of 2 parts) | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [z_motor_mount_front](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/z_motor_mount_front.stl) | 2        | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [z_tops](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/z_tops.stl) | 1 (total of 2 parts) | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [foot](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/foot.stl) | 4 | Filament | Print (priority 2)
3D Printed Part             | Full Bear MK3 - [psu_lower_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/psu_lower_mount.stl) | 1 | Filament | Print (priority 2)
3D Printed Part             | Full Bear MK3 - [psu_upper_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/psu_upper_mount.stl) | 2 | Filament | Print (priority 2)
3D Printed Part             | Full Bear MK3 - [rambo_base_lower_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_base_lower_mount.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [rambo_base_upper_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_base_upper_mount.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [rambo_lid_lower_hinge](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_lid_lower_hinge.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [rambo_lid_upper_hinge](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_lid_upper_hinge.stl) | 1 |  Filament |Print (priority 3)
3D Printed Part             | Full Bear MK3 - [lcd_support_a](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/lcd_support_a.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [lcd_support_b](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/lcd_support_b.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [cable_clip_lcd](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/cable_clip_lcd.stl) | 6 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [cable_clip_round](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/cable_clip_round.stl) | 5 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [cable_clip_ziptie](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/cable_clip_ziptie.stl) | 3 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [end_caps](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/end_caps.stl) | 2 (total of 4 parts) | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [end_cap_z_axis](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/end_cap_z_axis.stl) | 2 | Filament | Print (priority 3)
3D Printed Part             | Bear Extruder and X Axis MK3 - [x_carriage](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/mk3/x_carriage.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Bear Extruder and X Axis MK3 - [x_end_idler](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/common_to_all_versions/x_end_idler.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Bear Extruder and X Axis MK3 - [x_end_idler_idler_mount](https://www.thingiverse.com/thing:3308226/files) | 1 | Filament | Print (priority 1). Note: 5 mm bore version for E3D 2GT 20T idler
3D Printed Part             | Bear Extruder and X Axis MK3 - [cable_guide_back_a](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/common_to_all_versions/cable_guide_back_a.stl) | 1 | Filament | Print (Priority 3?). Note: Check if needed for Bondtech extruder?
3D Printed Part             | Bear Extruder and X Axis MK3 - [cable_guide_back_b](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/common_to_all_versions/cable_guide_back_b.stl) | 1 | Filament | Print (Priority 3?). Note: Check if needed for Bondtech extruder?
3D Printed Part             | Bear Extruder and X Axis MK3 - [bondtech_x_carriage_mk3](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/optional_parts/bondtech_x_carriage/printed_parts/bondtech_x_carriage_mk3.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Bear Extruder and X Axis MK3 - [x_carriage_back](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/mk3/x_carriage_back.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Original Prusa i3 MK3 - [y-belt-holder](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3/Printed-Parts/stl/y-belt-holder.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Original Prusa i3 MK3 - [Einsy case; Cable clips](https://github.com/prusa3d/Original-Prusa-i3/tree/MK3/Printed-Parts/stl) | 1 | Filament | Print (priority 3). Note: Use a [Bear alternative](https://www.thingiverse.com/thing:3239428)
3D Printed Part             | Original Prusa i3 MK3 - [LCD cover; LCD knob](https://github.com/prusa3d/Original-Prusa-i3/tree/MK3/Printed-Parts/stl) | 1 | Filament | Print (priority 3). Note: Use a Bear alternative: [This](https://www.thingiverse.com/thing:3385560) or [this](https://www.thingiverse.com/thing:2941711)
3D Printed Part             | Original Prusa i3 MK3 - [Heatbed cable cover](https://github.com/prusa3d/Original-Prusa-i3/tree/MK3/Printed-Parts/stl) | 1 | Filament | Print (priority 3)
Bearing                     | LMU8 Linear Bearing               | 10 | $55.50| Misumi [LMU8](https://us.misumi-ec.com/vona2/detail/110300026540/?ProductCode=LMU8)
Metal Rod                   | Z-Axis Rod - 8 mm diameter, 320 mm length  | 2 | $24 | Misumi [PSFJ8-320](https://us.misumi-ec.com/vona2/detail/110302634310/?ProductCode=PSFJ8-320)
Metal Rod                   | Y-Axis Rod - 8 mm diameter, 330 mm length  | 2 | $24 | Misumi [PSFJ8-330](https://us.misumi-ec.com/vona2/detail/110302634310/?ProductCode=PSFJ8-330)
Metal Rod                   | Z-Axis Rod - 8 mm diameter, 370 mm length  | 2 | $24 | Misumi [PSFJ8-370](https://us.misumi-ec.com/vona2/detail/110302634310/?ProductCode=PSFJ8-370)
Belt                        | 2GT Belt                          | 2 | $14.54 | Misumi [GBN8522GT-60](https://us.misumi-ec.com/vona2/detail/110302652060/?ProductCode=GBN8522GT-60)
Idler                       | 2GT 20 Tooth Idler, 6 mm width, 5 mm bore     | 2 | £10.40 | E3D [M-IDLER-T-GT2-P20-6-A-P5-H100](https://e3d-online.com/gates-powergripr-toothed-idler-6mm)
Pulley                      | 2GT 16 Tooth Pulley, 6 mm width, 5 mm bore    | 2 | £7.00 | E3D [M-PULLEY-GT2-16T-6-P5-C-H155](https://e3d-online.com/gates-powergrip-pulley-16-tooth-6mm)
Dowel Pin                   | Dowel Pin 24 mm length, 5mm diameter | 1 | $0.98 | Fastenal [90501](https://www.fastenal.com/products/details/90501)
Dowel Pin                   | Dowel Pin 15.8 mm length, 5mm diameter | 1 | $1.69 | All3D Makers [Bear X Axis Dowel Pin for E3D Gates 5mm bore idler](https://all3dmakers.com/collections/hardware/products/bear-x-axis-dowel-pin-for-e3d-gates-5mm-bore-idler)
Electronics Assembly        | Einsy Rambo 1.1                   | 1 | $120.00 | UltiMachine [EINSY RAMBo 1.1](https://ultimachine.com/collections/electronics/products/einsy-rambo-1-1), All3D Makers [MK3 EINSY RAMBo](https://all3dmakers.com/collections/electronics/products/mk3-einsy-rambo)
Electronics Assembly        | 2004 LCD Display - [RepRapDiscount Smart Controller](https://reprap.org/wiki/RepRapDiscount_Smart_Controller) | 1 | $16.70 | eBay
Fan                         | Print cooling fan | 1 | $8.69 | All3D Makers [MK3 Part Cooling Fan](https://all3dmakers.com/collections/electronics/products/mk3-part-cooling-fan)
Fan                         | Hotend fan | 1 | $5.13 | Mouser [369-MF40100V21UA99](https://www.mouser.com/ProductDetail/369-MF40100V21UA99), All3D Makers [Sunon MF40100V1-1000U-G99 Hotend Cooling Fan](https://all3dmakers.com/collections/electronics/products/sunon-mf40100v1-1000u-g99-hotend-cooling-fan)
Cable                       | Cable / pig tail for hot end fan | 1 | $1.69 | All3D Makers [700mm Pigtail wire with Molex connector](https://all3dmakers.com/collections/electronics/products/700mm-pigtail-wire-with-molex-connector)
Electronics Assembly        | PINDA 2 sensor | 1 | $15.99 | All3D Makers [P.I.N.D.A 2 Inductive Sensor](https://all3dmakers.com/collections/electronics/products/p-i-n-d-a-2-inductive-sensor)
Electronics Assembly        | Filament sensor | 1 | $16.17 | eBay (find supplier)
Heatbed                     | MK52 headbed | 1 | $89.99 | All3D Makers [24v MK52 Heat bed for Prusa MK3](https://all3dmakers.com/collections/electronics/products/24v-mk52-heat-bed-for-prusa-mk3)
Electronics Assembly        | MK3 24V Power Supply | 1 | $69.99 | All3D Makers [24V MK3 Power Supply Assembly with Power Panic](https://all3dmakers.com/collections/electronics/products/24v-250-watts-switching-power-supply)
Motors kit                  | Stepper motors kit | 1 | $124.99 | All3D Makers [Motor Kit for Bear Upgrade, MK2/3, Haribo and Zaribo Mod](https://all3dmakers.com/collections/electronics/products/motor-kit-for-bear-upgrade-mk2-3-and-haribo-mod)
Aluminum Y carriage         | Prusa i3 MK3 Aluminum Y carriage | 1 | $38.99 | All3D Makers [Prusa i3 MK3 Aluminum Y carriage](https://all3dmakers.com/collections/hardware/products/original-prusa-i3-mk3-3d-printer-aluminum-y-carriage?variant=14666953883763)
Spring Steel Sheet          | MK3 Spring Steel Sheet | 1 | $25.75 | BuildTak [FlexPlate MK3 - 9.5"x10"](https://www.buildtak.com/product/flexplate-surface/)
Print Surface               | Print Surface | 1 | $14.25 | BuiltTak [Original 3ED Printing Surface - 9"X10"](https://www.buildtak.com/product/buildtak-3d-printing-surface/)
Hardware                    | U-Bolts for LMU8U Bearings and nyloc nuts | 1 set | $7.69 | All3D Makers [U-Bolts for LMU8U Bearings](https://all3dmakers.com/collections/hardware/products/u-bolts-to-hold-the-lm8uu-bearings-to-the-y-carriage-on-the-mk2s)
Extruder                    | [Bondtech MK2/MK2S/MK3 upgrade kit with Bondtech gears](https://www.bondtech.se/en/product/prusa-i3-mk2-mk2s-extruder-upgrade/) | 1 | $115 | All3D makers [Prusa i3 MK2/MK2S Extruder Upgrade](https://all3dmakers.com/collections/electronics/products/prusa-i3-mk2-mk2s-extruder-upgrade)
Hotend                      | E3D V6, 1.75 mm nozzle, 24V | 1 | £43.00, $79.99| E3D [V6-175-24V](https://e3d-online.com/v6-all-metal-hotend), All3D Makers [MK3 E3DV6 Assembled Hotend](https://all3dmakers.com/collections/electronics/products/mk3-e3dv6-assembled-hotend)
Screw                        | M4 x 10mm button socket screw | 2 | $0.42 | Fastenal [MB2530010A20000](https://www.fastenal.com/products/details/MB2530010A20000)
Screw                        | M3 x 10mm socket cap screw    | 17 | $3.14 | Fastenal [MS2510010A20000](https://www.fastenal.com/products/details/MS2510010A20000)
Screw                        | M3 x 12mm socket cap screw    | 10 | $2.09 | Fastenal [MS2510012A20000](https://www.fastenal.com/products/details/MS2510012A20000)
Screw                        | M3 x 18mm socket cap screw    | 13 | $5.89 | Fastenal [MS2510018A20000](https://www.fastenal.com/products/details/MS2510018A20000)
Screw                        | M3 x 40mm socket cap screw    | 4 | $1.45 | Fastenal [MS2510040A20000](https://www.fastenal.com/products/details/MS2510040A20000)
Nut                          | M3 hex nut                    | 12 | $0.88 | Fastenal [MN2510000A20000](https://www.fastenal.com/products/details/MN2510000A20000)
Nut                          | M3 nyloc nut                  | 2 | $0.32| Fastenal [1L2510000A20000](https://www.fastenal.com/products/details/1L2510000A20000)
Nut                          | M3 square nut                 | 4 | $0.80 | Fastenal [0161907](https://www.fastenal.com/products/details/0161907)
Washer                       | M3 x 7 mm washer              | 9 | $0.29 | Fastenal [MW6330000A20000](https://www.fastenal.com/products/details/MW6330000A20000)
Filament                     | 1 kg PETG                     | 1 | $24.99 | Amazon [eSUN 3D 1.75mm PETG Orange Filament 1kg](https://www.amazon.com/eSUN-1-75mm-Filament-Printer-Semi-Transparent/dp/B010Y25QZ2)

### Upgrades
Assembly/Component Type     | Description                       | Quantity | Possible sources and notes 
--------------------------- | --------------------------------- | -------- | --------------------------
3D Printed Part             | Updated Y idler holder and Y belt holder | 1 | [Print](https://www.thingiverse.com/thing:3122625)

## Documentation

* [Prusa i3 Bear Full Upgrade MK3](https://github.com/gregsaun/prusa_i3_bear_upgrade/tree/master/full_upgrade/for_mk3/manual)
* [Original Prusa i3 MK3S Kit Assembly Manual](https://manual.prusa3d.com/c/Original_Prusa_i3_MK3S_kit_assembly)
* [Bondtech Prusa i3 Assembly Manual](https://github.com/BondtechAB/Bondtech_Prusa_i3/tree/master/Doc)
* [Bear X Axis and Bondtech Extruder](https://github.com/gregsaun/bear_extruder_and_x_axis/tree/master/optional_parts/bondtech_x_carriage)
* [Optional part for Prusa i3 Bear Upgrade](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/optional_parts.md)
* [Regular extruder temperature drops with firmwares 3.5.0 and 3.5.1](https://github.com/prusa3d/Prusa-Firmware/issues/1405)
