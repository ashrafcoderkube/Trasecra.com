# Excel Field Mappings

## Overview
This section outlines the possible headers that may be present in an Excel file, detailing the corresponding headers that the system can map to internal attributes. This flexible mapping allows the system to recognize data from various sources by standardizing commonly used header names.

### Possible Excel Headers

| **Possible Excel Headers**               |
|------------------------------------------|
| `Report No`, `ReportNumber`              |
| `Packet No`, `Stock #`, `RID`, `StockID` |
| `Shape`, `shp`                           |
| `Col`, `Color`                           |
| `Wgt`, `Weight`, `Size`, `CaratSize`, `CaratWeight`, `Ct`, `CtSize`, `Weight`, `Sz`, `Carats`, `Carat` |
| `Cr.Angle`, `Crown Angle`, `C.A`, `CA`   |
| `Cr.Height`, `Crown Height`, `C.H`, `CH` |
| `Pav.Angle`, `Pavilion Angle`, `P.A`, `PA` |
| `Pav.Height`, `P.H`, `PH`                |
| `ColorType`                              |
| `color_1`, `Fancy Color`, `Color`        |
| `color_intensity`, `Fancy Color Intensity`, `Intensity` |
| `color_overtone`, `Fancy Color Overtone`, `Overtone` |
| `Milky`, `Cloudy`, `milky Inclusion`     |
| `CB`, `Black Inclusion`,     |
| `CW`, `White Inclusion`                  |
| `inclusion_open`, `Open Inclusion`       |
| `Clarity`, `Clar`, `Purity`              |
| `Eye Clean`                              |
| `bgm`, `BGM`                             |
| `finish`                                 |
| `Cut`, `Cut Grade`, `CutGrade`           |
| `Pol`, `Polish`, `Finish`                |
| `Sym`, `Symmetry`, `Symetry`, `Sym-metry`|
| `FL`, `Fls`, `Fluorescence Intensity`, `Flo`, `Flr`, `FlrIntensity`, `Fluor`, `Fluorescence`, `FluorescenceIntensity` |
| `Lab`, `Cert`, `Certificate`, `Laboratory`, `LAB` |
| `cert_comment`, `Cert comment`           |
| `Location`, `Country`                    |
| `Ratio`                                  |
| `Rough Source`                           |
| `Disc %`, `Transectra Discount %`, `Net%`, `Back%`, `Discount %` |
| `PPC`, `Transectra Price`, `Price/Ct`, `Rate`, `Price Per Carat` |
| `Amount`                                 |
| `Length`, `Meas1`                        |
| `Width`, `Meas2`                         |
| `Depth`, `Meas3`                         |
| `Treatment`                              |
| `Shade`                                  |
| `brand_name`, `Brand`                    |
| `Girdle`                                 |
| `Culet`, `Culet Size`, `Cullet`          |
| `Image`, `Image 1`                       |
| `VideoLink`, `VideoURL 1`, `Video Link`, `Lab`, `Video` |
| `currency_code`                          |
| `currency_symbol`                        |
| `Rap`                                    |
| `Comments 1`, `Member Comment`, `Comment`|
| `Key To Symbols`, `Key to symbols`, `KeytoSymbols` |
| `Report Comments`, `ReportComments`      |
| `Report Date`, `Report Issue Date`       |
| `Star`, `Star Length`, `Str Ln`          |
| `Lower`, `Lr Half`                       |
| `Availability`                           |
| `Tracr Id`                               |
| `Diamond Type`                           |

---

### Accepted Values Mapping

This section details the accepted values for various fields in the system. These values are predefined to ensure consistency when working with diamond data.

#### Clarity
The possible accepted values for `clarity` field:
- `FL`, `IF`, `Loupe Clean`, `LC`, `VVS1`, `VVS2`, `VS1`, `VS2`, `SI1`, `SI2`, `SI3`, `I1`, `P1`, `I2`, `P2`, `I3`, `P3`

#### Shape
The possible accepted values for `shape` field:
- `LRAD`, `Pear`, `CMB`, `Triangular`, `Tapered Baguette`, `Circular Brilliant`, `Asscher Sq Emerald`, `Cushion All`, `Cushion`, `Emerald`, `Round`, `Square Emerald`, `Princess`, `Marquise`, `Asscher`, `Baguette`, `Tapered Bullet`, `Calf`, `Briolette`, `Bullets`, `Cushion Brilliant`, `Cushion Modified`, `EuropeanCut`, `Epaulette`, `Flanders`, `Half Moon`, `Heart`, `Hexagonal`, `Kite`, `Lozenge`, `Octagonal`, `Old Miner`, `Oval`, `Pentagonal`, `Radiant`, `Square Radiant`, `Rose`, `Shield`, `Square`, `Star`, `Trapezoid`, `Triangle`, `Trilliant`, `RD`, `SEM`, `RA`, `CU`, `EM`, `HT`, `MQ`, `OV`, `PE`, `PRIN`, `PR`, `HE`, `AS`, `SHMB`, `HXG`, `HXGdiamond`, `OVAL MODIFIED BRILLIANT`, `BUGGETTE`, `SQ.RADIANT`, `LONG RADIANT`, `Sq. Emerald`

#### Color
The possible accepted values for `color` field:
- Single letters from `D` to `Z`
- `S-T`, `GY G BN`, `F L Y`, `U-V`, `FL B Y`, `Yellow`, `Pink`, `Blue`, `Red`, `Green`, `Purple`, `Orange`, `Violet`, `Gray`, `Black`, `Brown`, `Champagne`, `Cognac`, `Chameleon`, `White`, `Purple-Pink`, `Green-Grey`, `Yellow-Brown`, `Yellow-Grey`, `Pink-Purple`, `Orange-Brown`

#### Cut
The possible accepted values for `cut` field:
- `I`, `Ideal`, `ID`, `EX`, `Excellent`, `EXC`, `VG`, `Very Good`, `G`, `Good`, `F`, `Fair`, `P`, `Poor`, `GD`, `FR`

#### Polish
The possible accepted values for `polish` field:
- `GD`, `I`, `ID`, `EX`, `Excellent`, `X`, `VG-EX`, `Very Good to Excellent`, `VGEX`, `VG`, `Very Good`, `V`, `V.Good`, `V.G`, `G-VG`, `Good to Very Good`, `G`, `Good`, `F-G`, `Fair to Good`, `F`, `Fair`, `P`, `Poor`

#### Symmetry
The possible accepted values for `symmetry` field:
- `FR`, `I`, `Ideal`, `ID`, `EX`, `Excellent`, `X`, `VG-EX`, `Very Good to Excellent`, `VGEX`, `VG`, `Very Good`, `V`, `V.G`, `G-VG`, `Good to Very Good`, `G`, `Good`, `F-G`, `Fair to Good`, `F`, `Fair`, `P`, `Poor`, `GD`

#### Fluorescence
The possible accepted values for `fluorescence` field:
- `VS`, `Very Strong`, `VST`, `FL4`, `S`, `Strong`, `STG`, `ST`, `FL3`, `M`, `Medium`, `MED`, `FL2`, `F`, `Faint`, `FNT`, `Negligible`, `FA`, `FL1`, `SL`, `Slight`, `SLI`, `VSL`, `Very Slight`, `VSLG`, `VSLT`, `N`, `None`, `NON`, `No`, `NIL`, `FL0`, `STR`, `FR`, `SL`, `SLT`, `STG`, `VSL`

#### Cutlet
The possible accepted values for `cutlet` field:
- `SML`, `EL`, `Extremely Large`, `VL`, `Very Large`, `L`, `Large`, `SL`, `Slightly Large`, `M`, `Medium`, `S`, `Small`, `VS`, `Very Small`, `N`, `None`, `vsm`, `POINTED`, `NONE`, `MED`, `LONG`

#### Inclusion White
The possible accepted values for `inclusion_white` field:
- `None`, `White Inclusions None`, `WT0`, `White Table Meaningless`, `WT1`, `White Table Small`, `WT2`, `White Table Medium`, `WT3`, `White Table Large`, `WC0`, `White Crown Meaningless`, `WC1`, `White Crown Small`, `WC2`, `White Crown Medium`, `WC3`, `White Crown Large`, `0`, `1`, `2`, `3`

#### Inclusion Black
The possible accepted values for `inclusion_black` field:
- `None`, `Black Inclusions None`, `BT0`, `Black Table Meaningless`, `BT1`, `Black Table Small`, `BT2`, `Black Table Medium`, `BT3`, `Black Table Large`, `BC0`, `Black Crown Meaningless`, `BC1`, `Black Crown Small`, `BC2`, `Black Crown Medium`, `BC3`, `Black Crown Large`, `BT1BC0`, `BT1 BC0`, `BT1 BC1`, `BT0 BC1`, `BT0 BC2`, `BT1 BC2`, `BT1 BC3`, `BT1 BCO`, `BT2 BC1`, `BT2 BC2`, `BT3 BC0`, `BT2 BC0`, `BTO BC1`, `0`, `1`, `2`, `3`

#### Inclusion Open
The possible accepted values for `inclusion_open` field:
- `None`, `Open Inclusions None`, `OT1`, `Open Table Small`, `OT2`, `Open Table Medium`, `OT3`, `Open Table Large`, `OC1`, `Open Crown Small`, `OC2`, `Open Crown Medium`, `OC3`, `Open Crown Large`, `OP1`, `Open Pavilion Small`, `OP2`, `Open Pavilion Medium`, `OP3`, `Open Pavilion Large`, `OG1`, `Open Girdle Small`, `OG2`, `Open Girdle Medium`, `OG3`, `Open Girdle Large`

#### Inclusion Milky
The possible accepted values for `inclusion_milky` field:
- `None`, `M0`, `Light`, `M1`, `Medium`, `M2`, `Heavy`, `M3`, `ML-0`, `ML-1`, `ML-2`, `ML-3`

#### Color Overtone
The possible accepted values for `color_overtone` field:
- `PINK CHAMPAGNE`, `PURPLISH RED`, `PURPLISH PINK`, `Yellow`, `Yellowish`, `Pink`, `Pinkish`, `Blue`, `Blueish`, `Red`, `Reddish`, `Green`, `Greenish`, `Purple`, `Purplish`, `Orange`, `Orangey`, `Violet`, `Gray`, `Grayish`, `Black`, `Brown`, `Brownish`, `Champagne`, `Cognac`, `Chameleon`

#### Color Intensity
The possible accepted values for `color_intensity` field:
- Values from `1PP` to `9PP`, `Faint`, `Very Light`, `Light`, `Fancy Light`, `Fancy`, `Fancy Dark`, `Fancy Intense`, `Fancy Vivid`, `Fancy Deep`

#### Fluorescence Color 
The possible accepted values for `Fluorescence color` field:
- `RED`, `PINK`, `CHAMPAGNE`, `BLUE`, `Yellow`, `Pink`, `Red`, `Green`, `Purple`, `Orange`, `Violet`, `gray`, `black`, `brown`, `Champagne`, `Cognac`, `Chameleon`, `White`
