# ASABE 2024 Robotics Competition Plant
This repository contains the files needed to print the simulation plant for the 2024 ASABE robotics competition. **Full rules can be found [here](https://docs.google.com/document/d/1JPMAodRuwTGvhz5UEUWVJHI-WIk5GcbBl3c8BVmr7d0/edit)**

# Terminology
| Term  | Definition                                                                      |
| ----- | ------------------------------------------------------------------------------- |
| Stalk | The central core which fits into the game board and holds stems                 |
| Stem  | The part that connects the stalk and leaves/flowers. It holds a 6mmx3mm magnet. |

# Assembly
Note: Quantities are provided as recommendations for a *fully populated **average** arena*. This is not necessarily indicative of the competition arena. For more information, see section 3 of [Performance Scoring](https://docs.google.com/document/d/1JPMAodRuwTGvhz5UEUWVJHI-WIk5GcbBl3c8BVmr7d0/edit#heading=h.aye7t6q3p1dy)
| Component                       | Quantity          | Link                                                                                                                                                |
| ------------------------------- | ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| White PETG Filament             | 1                 | [Amazon](https://www.amazon.com/OVERTURE-Filament-Consumables-Dimensional-Accuracy/dp/B07PDV9RC8/)                                                  |
| 6 x 2 mm Neodymium Magnet       | 1 per stem        | [Amazon](https://www.amazon.com/dp/B096LYVGPS/)                                                                                                     |
| Upholstery Tack (8 mm Diameter) | 1 per flower/leaf | [Amazon](https://www.amazon.com/dp/B07KKFRQXT/)                                                                                                     |
| Stalk                           | 24                | [Beginner](Beginner/Beginner_Trunk.stl)/[Advanced](Advanced/Advanced_Trunk.stl)                                                                     |
| Stem (Short)                    | 64                | [STL](Stem_Short.stl)                                                                                                                               |
| Stem (Medium)                   | 64                | [STL](Stem_Medium.stl)                                                                                                                              |
| Stem (Long)                     | 64                | [STL](Stem_Long.stl)                                                                                                                                |
| Leaves                          | 96                | [STL](Leaves.stl)                                                                                                                                   |
| Flower                          | 32                | [STL](Flower.stl)                                                                                                                                   |
| Spray Paint (Healthy Leaf)      | 1                 | [Gloss Meadow Green](https://www.homedepot.com/p/Rust-Oleum-Painter-s-Touch-2X-12-oz-Gloss-Green-General-Purpose-Spray-Paint-334039/307244868)      |
| Spray Paint (Unhealthy Leaf)    | 1                 | [Satin Green Apple](https://www.homedepot.com/p/Rust-Oleum-Painter-s-Touch-2X-12-oz-Satin-Green-Apple-General-Purpose-Spray-Paint-334070/307244897) |
| Spray Paint (Stem/Stalk)        | 1                 | [Satin Moss Green](https://www.homedepot.com/p/Rust-Oleum-Painter-s-Touch-2X-12-oz-Satin-Moss-Green-General-Purpose-Spray-Paint-334075/307244920)   |

## 3D Printing Notes
The manufacture of the 2023 ASABE plant requires 3D printing. If you do not have a 3D printer, there are good options at or around the 200$ USD price point. Alternatively, there are many online brokers out there that can get the parts printed at a very price. For one beginner row (12 beginner trunks, 64 long stems, 16 flowers, 48 leaves) [craftcloud3d](craftcloud3d.com) claims to be able to get the job done for ~50$.

If printing yourself, be aware that the specified **PETG filament has different properties to common PLA**. It is significantly more flexible and tough which affects how the simulation plants react to disturbances. We highly recommend using it.

Note that PETG filament can absorb water over time. If you're having excessive stringing, problems with bed adhesion, bumps on the extruded filament when loading, or poor surface quality, you may need to [dry your filament](https://help.prusa3d.com/article/drying-filament_332086).

## Instructions
1. Print stalks, leaves, flowers, and stems using white PETG filament. 
   1. If desired, CAD files may be modified as needed to achieve reliable press fits in the steps below (given your printer / material).
   2. The quantities provided in the component table provide our recommendation for a full field's worth of plants. **We recommend printing one of each part first to validate tolerances before printing more.**
   3. If desired, the "thick" versions of leaves/flowers may be printed for extra robustness. Note that the standard thickness (0.4mm) leaves/flowers will be used at competition.
   4. A full field will consist of *up to* 192 total stems. *For testing*, we recommend equally distributing this total among the three provided sizes (64 short, 64 medium, 64 long). Note that the actual distribution will **not** be announced.
2. Spray paint all components. 
   1. Leaves should be roughly split between the "healthy" and "unhealthy" color.
   2. Stems and stalks should be painted the "healthy" color
   3. Both sides of all components should be painted. We recommend painting all components of the same color at the same time.
3. Press a 6x3mm magnet into the bottom of each stem. ![Assembly Example](img/asm-press.png)
4. Press a thumb tack into the bottom of every flower and leaf. Some light hammering might be required. ![Assembly Example](img/asm-leaf.png)
5. Trim thumb tack stickout using diagonal cutters. 
   1. **WEAR SAFETY GLASSES!! - Trimmed pieces can fly in unpredictable directions.**
6. Glue assembled stems into the stalks according to your own discretion. 
   1. Each stalk should have 6-8 attached stems.
   2. The competition distribution will not be announced. Try to vary lengths and positions to maximize testing effectiveness.
   3. See the [advanced](https://a360.co/3RiKY86) and [beginner](https://a360.co/4aaLmyi) assemblies for an example.
7. Congratulations! Your plant(s) are now be assembled! Good luck, and we look forward to seeing you at the 2024 ASABE Robotics Competition!

# Division Differences
The competition is split into two divisions. More information about the differences between these two can be found in the [2024 release](https://docs.google.com/document/d/1JPMAodRuwTGvhz5UEUWVJHI-WIk5GcbBl3c8BVmr7d0/edit).

## Beginner [(Rules)](https://docs.google.com/document/d/1JPMAodRuwTGvhz5UEUWVJHI-WIk5GcbBl3c8BVmr7d0/edit#heading=h.k9yfkjzcqhdu)
Example Assembly: https://a360.co/4aaLmyi

For the beginner division, all stems are placed on the same level.

## Advanced [(Rules)](https://docs.google.com/document/d/1JPMAodRuwTGvhz5UEUWVJHI-WIk5GcbBl3c8BVmr7d0/edit#heading=h.ouqn01p8ic3i)

Example Assembly: https://a360.co/3RiKY86

For the advanced division, both the vertical and radial position of a given leaf or flower can vary. Stem radii can vary from 1.2" - 2.25" from the center of the stalk. Depending on the plant's position within the field, the height of the stem can also vary from between 2.75" - 7.25" above the arena surface. *For specific and up-to-date information, see [section 9 of the advanced division rules](https://docs.google.com/document/d/1JPMAodRuwTGvhz5UEUWVJHI-WIk5GcbBl3c8BVmr7d0/edit#heading=h.ouqn01p8ic3i)*