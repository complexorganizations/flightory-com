## Types of LW-PLA

On the market, there are many types of LW-PLA available. The key difference among them is whether they are in the prefoamed or active foaming technology. Both types of filaments are well-suited for printing airplanes; however, recommended print settings will differ between them. Prefoamed filaments are typically more expensive, but they offer the potential for higher print quality and a lower risk of artifacts that may occasionally occur during active foaming printing.

## How are Flightory aircraft designed?

Flightory airplanes are designed primarily for printing with LW-PLA, with additional components printed from rigid materials such as PET-G, PLA, or ABS. Each airplane has its own instructions, specifying settings for infill and wall line count for each individual part. The general rule is to print fuselages with a gyroid infill of 3%, while wings should be printed with a cubic subdivision infill of 3%. If there are any exceptions, they are noted in the instructions for a specific aircraft. Infill settings and wall thickness can be configured and changed; however, the selected settings represent an optimal compromise between the durability and strength of the airframe and its weight. The airplanes are designed to be printable on standard, inexpensive printers with a small working area. Most elements fit within a 220x220x250mm working area. Prototypes are tested on Tarantula Pro printers with a standard 0.4mm nozzle. Many users, however, choose to make modifications and experiment with other materials, such as printing whole airframes with ABS, PLA, or other harder materials. While this is possible, it should be noted that it may result in increased weight and require different settings optimized for the specific material being used.

## Optimal print settings

The recommended slicer for Flightory models is Ultimaker Cura, as it offers extensive configuration possibilities and produces great printing results. Below are detailed settings for Active Foaming and Prefoamed LW-PLA. Many settings overlap, but there are specific differences in temperature, retract, and flow. If you want to use other slicers, you can experiment based on these settings. Below are the detailed print settings for Cura Slicer.

## Filament used for printing Flightory prototypes

Below are the detailed print settings in the Cura slicer for active foaming and prefoamed LW-PLA. It’s important to note that the filaments used for these settings are eSUN ePLA-LW (active foaming) and Polymaker Polylite LW-PLA (prefoamed). Other manufacturers’ filaments can also be used successfully, but there may be some differences between them that might require tuning the settings, such as slight adjustments in temperature, flow, retraction, etc. Feel free to experiment and share your experiences with the **community.**

## Active Foaming LW-PLA Settings

| Quality                  |         |
| ------------------------ | ------- |
| Layer Height             | 0.25 mm |
| Initial Layer Height     | 0.25 mm |
| Line Width               | 0.4 mm  |
| Wall Line Width          | 0.4 mm  |
| Outer Wall Line Width    | 0.4 mm  |
| Inner Wall(s) Line Width | 0.4 mm  |
| Top/Bottom Line Width    | 0.4 mm  |
| Infill Line Width        | 0.4 mm  |
| Skirt/Brim Line Width    | 0.4 mm  |
| Initial Layer Line Width | 100%    |

### Walls

| Walls                              |                   |
| ---------------------------------- | ----------------- |
| Wall Thickness                     | 0.4 mm            |
| Wall Line Count                    | 1                 |
| Outer Wall Wipe Distance           | 0.0 mm            |
| Outer Wall Inset                   | 0.0 mm            |
| Optimize Wall Printing Order       | ✅                |
| Wall Ordering                      | Inside to Outside |
| Alternate Extra Wall               | ⬜                |
| Print Thin Walls                   | ✅                |
| Horizontal Expansion               | 0.0 mm            |
| Initial Layer Horizontal Expansion | 0.0 mm            |
| Hole Horizontal Expansion          | 0.0 mm            |
| Z Seam Alignment                   | Sharpest Corner   |
| Seam Corner Preference             | Smart Hiding      |

### Top/Bottom

| Top/Bottom                       |         |
| -------------------------------- | ------- |
| Top Surface Skin Layers          | 0       |
| Top/Bottom Thickness             | 0.75 mm |
| Top Thickness                    | 0.75 mm |
| Top Layers                       | 3       |
| Bottom Thickness                 | 0.75 mm |
| Bottom Layers                    | 3       |
| Top/Bottom Pattern               | Lines   |
| Bottom Pattern Initial Layer     | Lines   |
| Monotonic Top/Bottom Order       | ⬜      |
| Top/Bottom Line Directions       | ⬜      |
| No Skin in Z Gaps                | ⬜      |
| Extra Skin Wall Count            | 1       |
| Enable Ironing                   | ⬜      |
| Skin Overlap Percentage          | 10%     |
| Skin Overlap                     | 0.04 mm |
| Skin Removal Width               | 0.4 mm  |
| Top Skin Removal Width           | 0.4 mm  |
| Bottom Skin Removal Width        | 0.4 mm  |
| Skin Expand Distance             | 0.4 mm  |
| Top Skin Expand Distance         | 0.4 mm  |
| Bottom Skin Expand Distance      | 0.4 mm  |
| Maximum Skin Angle for Expansion | 90°     |
| Minimum Skin Width for Expansion | 0.0 mm  |

### Infill (Gyroid)

| Infill (Gyroid)             |           |
| --------------------------- | --------- |
| Infill Density              | 3%        |
| Infill Line Distance        | 13.333 mm |
| Infill Pattern              | Gyroid    |
| Connect Infill Lines        | ⬜        |
| Randomize Infill Start      | ⬜        |
| Infill Line Multiplier      | 1         |
| Extra Infill Wall Count     | 0         |
| Infill Overlap Percentage   | 10%       |
| Infill Overlap              | 0.04 mm   |
| Infill Wipe Distance        | 0.1 mm    |
| Infill Layer Thickness      | 0.25 mm   |
| Gradual Infill Steps        | 0         |
| Infill Before Walls         | ⬜        |
| Infill Minimum Area         | 0.0 mm    |
| Infill Support              | ⬜        |
| Skin Edge Support Thickness | 0.0 mm    |
| Skin Edge Support Layers    | 0         |

### Infill (Cubic Subdivision)

| Infill (Cubic Subdivision)  |                   |
| --------------------------- | ----------------- |
| Infill Density              | 3%                |
| Infill Line Distance        | 40.0 mm           |
| Infill Pattern              | Cubic Subdivision |
| Infill Line Directions      | ⬜                |
| Randomize Infill Start      | ⬜                |
| Infill Line Multiplier      | 1                 |
| Cubic Subdivision Shell     | 0.4 mm            |
| Infill Overlap Percentage   | 10%               |
| Infill Overlap              | 0.04 mm           |
| Infill Wipe Distance        | 0.1 mm            |
| Infill Layer Thickness      | 0.25 mm           |
| Gradual Infill Steps        | 0                 |
| Infill Before Walls         | ⬜                |
| Infill Minimum Area         | 0.0 mm            |
| Infill Support              | ⬜                |
| Skin Edge Support Thickness | 0.0 mm            |
| Skin Edge Support Layers    | 0                 |

### Material

| Material                                         |        |
| ------------------------------------------------ | ------ |
| Printing Temperature                             | 235 °C |
| Printing Temperature Initial Layer               | 235 °C |
| Initial Printing Temperature                     | 235 °C |
| Final Printing Temperature                       | 235 °C |
| Build Plate Temperature                          | 60 °C  |
| Build Plate Temperature Initial Layer            | 60 °C  |
| Scaling Factor Shrinkage Compensation            | 100%   |
| Horizontal Scaling Factor Shrinkage Compensation | 100%   |
| Vertical Scaling Factor Shrinkage Compensation   | 100%   |
| Flow                                             | 60%    |
| Wall Flow                                        | 60%    |
| Outer Wall Flow                                  | 60%    |
| Inner Wall(s) Flow                               | 60%    |
| Top/Bottom Flow                                  | 60%    |
| Infill Flow                                      | 60%    |
| Skirt/Brim Flow                                  | 60%    |
| Prime Tower Flow                                 | 60%    |
| Initial Layer Flow                               | 80%    |

### Speed

| Speed                       |          |
| --------------------------- | -------- |
| Print Speed                 | 60 mm/s  |
| Infill Speed                | 60 mm/s  |
| Wall Speed                  | 30 mm/s  |
| Outer Wall Speed            | 30 mm/s  |
| Inner Wall Speed            | 30 mm/s  |
| Top/Bottom Speed            | 30 mm/s  |
| Travel Speed                | 120 mm/s |
| Initial Layer Speed         | 30 mm/s  |
| Initial Layer Print Speed   | 30 mm/s  |
| Initial Layer Travel Speed  | 120 mm/s |
| Skirt/Brim Speed            | 30 mm/s  |
| Number of Slower Layers     | 2        |
| Flow Equalization Ratio     | 100%     |
| Enable Acceleration Control | ⬜       |
| Enable Jerk Control         | ⬜       |

### Travel

| Travel                            |          |
| --------------------------------- | -------- |
| Enable Retraction                 | ✅       |
| Retract at Layer Change           | ⬜       |
| Retraction Distance               | 0.0 mm   |
| Retraction Speed                  | 35 mm/s  |
| Retraction Retract Speed          | 35 mm/s  |
| Retraction Prime Speed            | 35 mm/s  |
| Retraction Extra Prime Amount     | 0.3 mm   |
| Retraction Minimum Travel         | 1.5 mm   |
| Maximum Retraction Count          | 90       |
| Minimum Extrusion Distance Window | 6.5 mm   |
| Combing Mode                      | All      |
| Avoid Supports When Traveling     | ✅       |
| Travel Avoid Distance             | 0.625 mm |
| Layer Start X                     | 0.0 mm   |
| Layer Start Y                     | 0.0 mm   |
| Z Hop When Retracted              | ⬜       |

### Cooling

| Cooling                             |         |
| ----------------------------------- | ------- |
| Enable Print Cooling                | ⬜      |
| Regular/Maximum Fan Speed Threshold | 10 s    |
| Regular Fan Speed at Height         | 0.27 mm |
| Regular Fan Speed at Layer          | 2       |
| Minimum Layer Time                  | 2.0 s   |
| Maximum Speed                       | 10 mm/s |
| Lift Head                           | ⬜      |

### Support

| Support          |     |
| ---------------- | --- |
| Generate Support | ⬜  |

### Build Plate Adhesion

| Build Plate Adhesion      |        |
| ------------------------- | ------ |
| Build Plate Adhesion Type | Brim   |
| Skirt/Brim Minimum Length | 250 mm |
| Brim Width                | 8.0 mm |
| Brim Line Count           | 20     |
| Brim Distance             | 0.0 mm |
| Brim Only on Outside      | ✅     |

## Prefoamed LW-PLA Settings

| Quality                  |         |
| ------------------------ | ------- |
| Layer Height             | 0.25 mm |
| Initial Layer Height     | 0.25 mm |
| Line Width               | 0.4 mm  |
| Wall Line Width          | 0.4 mm  |
| Outer Wall Line Width    | 0.4 mm  |
| Inner Wall(s) Line Width | 0.4 mm  |
| Top/Bottom Line Width    | 0.4 mm  |
| Infill Line Width        | 0.4 mm  |
| Skirt/Brim Line Width    | 0.4 mm  |
| Initial Layer Line Width | 100%    |

### Walls

| Walls                              |                   |
| ---------------------------------- | ----------------- |
| Wall Thickness                     | 0.4 mm            |
| Wall Line Count                    | 1                 |
| Outer Wall Wipe Distance           | 0.0 mm            |
| Outer Wall Inset                   | 0.0 mm            |
| Optimize Wall Printing Order       | ✅                |
| Wall Ordering                      | Inside to Outside |
| Alternate Extra Wall               | ⬜                |
| Print Thin Walls                   | ✅                |
| Horizontal Expansion               | 0.0 mm            |
| Initial Layer Horizontal Expansion | 0.0 mm            |
| Hole Horizontal Expansion          | 0.0 mm            |
| Z Seam Alignment                   | Sharpest Corner   |
| Seam Corner Preference             | Smart Hiding      |

### Top/Bottom

| Top/Bottom                       |         |
| -------------------------------- | ------- |
| Top Surface Skin Layers          | 0       |
| Top/Bottom Thickness             | 0.75 mm |
| Top Thickness                    | 0.75 mm |
| Top Layers                       | 3       |
| Bottom Thickness                 | 0.75 mm |
| Bottom Layers                    | 3       |
| Top/Bottom Pattern               | Lines   |
| Bottom Pattern Initial Layer     | Lines   |
| Monotonic Top/Bottom Order       | ⬜      |
| Top/Bottom Line Directions       | ⬜      |
| No Skin in Z Gaps                | ⬜      |
| Extra Skin Wall Count            | 1       |
| Enable Ironing                   | ⬜      |
| Skin Overlap Percentage          | 10%     |
| Skin Overlap                     | 0.04 mm |
| Skin Removal Width               | 0.4 mm  |
| Top Skin Removal Width           | 0.4 mm  |
| Bottom Skin Removal Width        | 0.4 mm  |
| Skin Expand Distance             | 0.4 mm  |
| Top Skin Expand Distance         | 0.4 mm  |
| Bottom Skin Expand Distance      | 0.4 mm  |
| Maximum Skin Angle for Expansion | 90°     |
| Minimum Skin Width for Expansion | 0.0 mm  |

### Infill (Gyroid)

| Infill (Gyroid)             |           |
| --------------------------- | --------- |
| Infill Density              | 3%        |
| Infill Line Distance        | 13.333 mm |
| Infill Pattern              | Gyroid    |
| Connect Infill Lines        | ⬜        |
| Randomize Infill Start      | ⬜        |
| Infill Line Multiplier      | 1         |
| Extra Infill Wall Count     | 0         |
| Infill Overlap Percentage   | 10%       |
| Infill Overlap              | 0.04 mm   |
| Infill Wipe Distance        | 0.1 mm    |
| Infill Layer Thickness      | 0.25 mm   |
| Gradual Infill Steps        | 0         |
| Infill Before Walls         | ⬜        |
| Infill Minimum Area         | 0.0 mm    |
| Infill Support              | ⬜        |
| Skin Edge Support Thickness | 0.0 mm    |
| Skin Edge Support Layers    | 0         |

### Infill (Cubic Subdivision)

| Infill (Cubic Subdivision)  |                   |
| --------------------------- | ----------------- |
| Infill Density              | 3%                |
| Infill Line Distance        | 40.0 mm           |
| Infill Pattern              | Cubic Subdivision |
| Infill Line Directions      | ⬜                |
| Randomize Infill Start      | ⬜                |
| Infill Line Multiplier      | 1                 |
| Cubic Subdivision Shell     | 0.4 mm            |
| Infill Overlap Percentage   | 10%               |
| Infill Overlap              | 0.04 mm           |
| Infill Wipe Distance        | 0.1 mm            |
| Infill Layer Thickness      | 0.25 mm           |
| Gradual Infill Steps        | 0                 |
| Infill Before Walls         | ⬜                |
| Infill Minimum Area         | 0.0 mm            |
| Infill Support              | ⬜                |
| Skin Edge Support Thickness | 0.0 mm            |
| Skin Edge Support Layers    | 0                 |

### Material

| Material                                         |        |
| ------------------------------------------------ | ------ |
| Printing Temperature                             | 210 °C |
| Printing Temperature Initial Layer               | 210 °C |
| Initial Printing Temperature                     | 210 °C |
| Final Printing Temperature                       | 210 °C |
| Build Plate Temperature                          | 60 °C  |
| Build Plate Temperature Initial Layer            | 60 °C  |
| Scaling Factor Shrinkage Compensation            | 100%   |
| Horizontal Scaling Factor Shrinkage Compensation | 100%   |
| Vertical Scaling Factor Shrinkage Compensation   | 100%   |
| Flow                                             | 100%   |
| Wall Flow                                        | 100%   |
| Outer Wall Flow                                  | 100%   |
| Inner Wall(s) Flow                               | 100%   |
| Top/Bottom Flow                                  | 100%   |
| Infill Flow                                      | 100%   |
| Skirt/Brim Flow                                  | 100%   |
| Prime Tower Flow                                 | 100%   |
| Initial Layer Flow                               | 100%   |

### Speed

| Speed                       |          |
| --------------------------- | -------- |
| Print Speed                 | 60 mm/s  |
| Infill Speed                | 60 mm/s  |
| Wall Speed                  | 30 mm/s  |
| Outer Wall Speed            | 30 mm/s  |
| Inner Wall Speed            | 30 mm/s  |
| Top/Bottom Speed            | 30 mm/s  |
| Travel Speed                | 120 mm/s |
| Initial Layer Speed         | 30 mm/s  |
| Initial Layer Print Speed   | 30 mm/s  |
| Initial Layer Travel Speed  | 120 mm/s |
| Skirt/Brim Speed            | 30 mm/s  |
| Number of Slower Layers     | 2        |
| Flow Equalization Ratio     | 100%     |
| Enable Acceleration Control | ⬜       |
| Enable Jerk Control         | ⬜       |

### Travel

| Travel                            |          |
| --------------------------------- | -------- |
| Enable Retraction                 | ✅       |
| Retract at Layer Change           | ⬜       |
| Retraction Distance               | 6.0 mm   |
| Retraction Speed                  | 50 mm/s  |
| Retraction Retract Speed          | 50 mm/s  |
| Retraction Prime Speed            | 50 mm/s  |
| Retraction Extra Prime Amount     | 0.0 mm   |
| Retraction Minimum Travel         | 1.5 mm   |
| Maximum Retraction Count          | 90       |
| Minimum Extrusion Distance Window | 6.5 mm   |
| Combing Mode                      | All      |
| Avoid Supports When Traveling     | ✅       |
| Travel Avoid Distance             | 0.625 mm |
| Layer Start X                     | 0.0 mm   |
| Layer Start Y                     | 0.0 mm   |
| Z Hop When Retracted              | ⬜       |

### Cooling

| Cooling                             |         |
| ----------------------------------- | ------- |
| Enable Print Cooling                | ✅      |
| Regular/Maximum Fan Speed Threshold | 10 s    |
| Regular Fan Speed at Height         | 0.27 mm |
| Regular Fan Speed at Layer          | 2       |
| Minimum Layer Time                  | 2.0 s   |
| Maximum Speed                       | 10 mm/s |
| Lift Head                           | ⬜      |

### Support

| Support          |     |
| ---------------- | --- |
| Generate Support | ⬜  |

### Build Plate Adhesion

| Build Plate Adhesion      |        |
| ------------------------- | ------ |
| Build Plate Adhesion Type | Brim   |
| Skirt/Brim Minimum Length | 250 mm |
| Brim Width                | 8.0 mm |
| Brim Line Count           | 20     |
| Brim Distance             | 0.0 mm |
| Brim Only on Outside      | ✅     |

These settings are intended to optimize the printing process for Prefoamed LW-PLA, ensuring a balance between print quality and material efficiency. Adjustments may be necessary based on specific printer models and environmental conditions.
