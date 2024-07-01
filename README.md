# 180mm3-Printer-Name-TBD
Files and design for my 180mm^3 printer

Few design ideas right now


Motherboard - BTT V1.4 w/ MOTv1.0 for a total of 8 stepper motors


Power Supply - MeanWell 24V 350W Power Supply 


Heated Bed: Custom with something idk yet


Stepper Motors - 


Nozzle - Hardened CHT Nozzle with standard M6 Threads. 


Extruder - Sherpa Mini


Display: Will get octoprint set up, but also hoping for a nice touchscreen


Firmware: I will get a custom klipper profile set up


Auto Leveling: I will have autoleveling, just unsure as to how. 


Core XY machine, 3 Motor Leadscrew with kinematic joints to have tramming


Enclosed, hoping to reach chamber temps of ~60C at least, 


Hotend: Phateus Rapido HF


Nevermore Carbon Filter to allow for printing of all materials safely. 


Above all, this should be fast. Very Fast. And relatively cheap and easy to make. And, it should be able to print some "engineering grade materials". Finally, fun is the #1 priority

Links:
Onshape:  https://cad.onshape.com/documents/ea3003fedda180a5827edece/w/24975c8a2f1006566d68c26a/e/f749387482ee518d7d44cc61


BTT Motherboards: [https://biqu.equipment/products/bigtreetech-skr-pro-v1-1-32-bit-control-board?variant=29207358865506 / https://biqu.equipment/products/bigtreetech-skr-v1-4-skr-v1-4-turbo-control-board?_pos=1&_psq=1.4%20turbo&_ss=e&_v=1.0&variant=40048265822306
](https://biqu.equipment/products/bigtreetech-octopus-pro-v1-0-chip-f446?variant=40144816767074)

Heated Bed: https://www.prusa3d.com/product/magnetic-heatbed-mini-24v/


PEI Sheets: /shrug


Stepper Motors: LDO Nema_17_42STH48-2504AC for the X,Y, and all three Z Motors. 46mm shaft on the x and y motors to remove a cantilever
https://www.filastruder.com/products/ldo-stepper-motors-all-types?variant=39923122339911
https://www.fabreeko.com/products/ldo-42sth48-2504ah-high-temp?_pos=1&_sid=e448f3753&_ss=r



Power Supply: https://www.amazon.com/MEAN-WELL-LRS-350-24-Switching-Printer/dp/B07SQLJG5L/ref=sr_1_3?hvadid=570433200159&hvdev=c&hvlocphy=9001951&hvnetw=g&hvqmt=e&hvrand=8415374557647128318&hvtargid=kwd-297537352961&hydadcr=19107_13375052&keywords=meanwell%2B24v%2B350w&qid=1696872093&sr=8-3&th=1


Extruder: https://www.filastruder.com/products/ldo-sherpa-mini-extruder


Nozzle: 


Linear Rails: https://www.amazon.com/Miniature-Linear-Bearing-Printer-Machine/dp/B07HH5L5FK or https://www.amazon.com/ANWOKIT-Miniature-Sliding-Printer-Machine/dp/B0BS9KL2H9/ref=sr_1_4?crid=3QSJXQN90B4NZ&keywords=MGN12%2B300mm%2BMiniature%2BLinear%2BRail&qid=1697833757&s=industrial&sprefix=mgn12%2B300mm%2Bminiature%2Blinear%2Brail%2Cindustrial%2C105&sr=1-4&th=1

Honeybadger rails: https://www.fabreeko.com/collections/honeybadger/products/honeybadger-mgn12c-stainless-steel-rails?variant=42106258161919

https://www.amazon.com/ANWOKIT-Miniature-Sliding-Printer-Machine/dp/B0BS9KL2H9/ref=sr_1_4?crid=3QSJXQN90B4NZ&keywords=MGN12%2B300mm%2BMiniature%2BLinear%2BRail&qid=1697833757&s=industrial&sprefix=mgn12%2B300mm%2Bminiature%2Blinear%2Brail%2Cindustrial%2C105&sr=1-4&th=1

https://www.amazon.com/OUYZGIA-MGN12-Linear-Rail-US/dp/B09ZNY4C4P?th=1

Hotend: https://www.matterhackers.com/store/l/phaetus-rapido-plus-2-hotend/sk/M56YAPMU or https://west3d.com/products/rapido-hot-end-high-flow-tl-phaetus?variant=43817479241940


Leadscrew: https://www.amazon.com/HAWKUNG-Stainless-Threaded-Printer-Machine/dp/B07P6HQMHT/ref=sr_1_2?crid=YUWJ4SLLUF71&keywords=steel%2Bt8%2Bleadscrew%2B300mm&qid=1697238579&s=industrial&sprefix=steel%2Bt8%2Bleadscrew%2B300mm%2Cindustrial%2C59&sr=1-2&th=1 OR https://ratrig.com/acme-8mm-lead-screw.html (290mm)


Coupler: https://www.amazon.com/Saiper-Couplings-Connector-Compatible-Accessories/dp/B07MGN29RD and https://ratrig.com/rat-rig-bi-material-lead-screw-decoupler.html


POM Nuts: https://www.amazon.com/Printer-Backlash-Threaded-Eliminate-Accessories/dp/B07XYQ4KJ9/ref=sr_1_3?crid=1LJ4PT1ICKPNR&keywords=Tr8x8%2BPOM&qid=1698028499&sprefix=tr8x8%2Bpom%2Caps%2C86&sr=8-3&th=1





XY MOTION SYSTEM

IDLER PULLEY: https://ratrig.com/idler-pulley-toothed-for-2gt-20t-5mm-bore-multiple-sizes-and-types.html

DRIVE PULLEY: https://ratrig.com/openbuilds-gt2-2mm-aluminum-timing-pulley-9mm.html

STEPPER: SEE ABOVE

SHAFT COUPLER: https://www.amazon.com/Saiper-Couplings-Connector-Compatible-Accessories/dp/B07MGN29RD 5mm to 5mm

https://us.misumi-ec.com/vona2/detail/110302686450/?Tab=wysiwyg_area_0&curSearch=%7B%22field%22:%22@search%22,%22seriesCode%22:%22110302686450%22,%22innerCode%22:%22%22,%22sort%22:1,%22specSortFlag%22:0,%22allSpecFlag%22:0,%22page%22:1,%22pageSize%22:%2260%22,%2200000042719%22:%22a%22,%2200000042737%22:%22b%22,%2200000332720%22:%222000%22,%22cadType%22:%222%22,%22fixedInfo%22:%22MDM00001301520110302686450-1897579906-1255582774045885826%7C13%22%7D
https://us.misumi-ec.com/vona2/detail/110302251660/?CategorySpec=unitType::1%0900000042748::c%0900000042759::a,j
https://ratrig.com/t-nut-square-for-3030-m5-single.html
