# Awesome-Construction-Site-Analytics

# Top Construction Site Analytics Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Reality Capture, Progress Tracking, Computer Vision, Drone Analytics, 360° Site Intelligence & Field Insights*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Construction Site Analytics**. These systems use cameras, drones, 360° capture, computer vision, and project data to measure progress, compare as-built vs design, monitor safety, and deliver objective site intelligence.

**Examples** include Doxel, Buildots, Versatile, WakeCap, OpenSpace, Disperse, Avvir, DroneDeploy, HammerTech, and Procore Analytics (the category leaders).

**Open-source emphasis**: Production-grade AI progress tracking and reality-to-BIM analytics are almost entirely commercial. Open options focus on **drone mapping**, **reality capture toolkits**, **computer vision prototypes**, and BIM comparison experiments. This section expands those building blocks while remaining realistic about the commercial gap.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Doxel](https://www.doxel.ai/)**  
  AI construction progress tracking using computer vision and site data to measure installed work against plans.

- **[Buildots](https://www.buildots.com/)**  
  Computer vision and deep learning platform that turns site capture into objective progress vs plan insights.

- **[Versatile](https://www.versatile.ai/)**  
  Construction site intelligence and productivity analytics using sensors and data from the field.

- **[WakeCap](https://www.wakecap.com/)**  
  Wearable and site analytics platform for labor, safety, and operational visibility on construction projects.

- **[OpenSpace](https://www.openspace.ai/)**  
  Reality capture platform for 360° walks, visual jobsite records, and AI-assisted progress and documentation insights.

- **[Disperse](https://www.disperse.io/)**  
  Construction progress and productivity analytics combining site capture with project controls insights.

- **[Avvir](https://www.avvir.io/)**  
  Reality capture and BIM comparison platform for verifying as-built conditions against design models.

- **[DroneDeploy](https://www.dronedeploy.com/)**  
  Reality capture platform for drones, robotics, and AI—maps, 3D models, and site analytics for construction and industrial sites.

- **[HammerTech](https://www.hammertech.com/)**  
  Construction safety, quality, and site management platform with analytics and field reporting capabilities.

- **[Procore Analytics](https://www.procore.com/)**  
  Analytics and reporting layer within the Procore construction management platform for project and portfolio insights.

## Open-Source GitHub Projects
- **[OpenDroneMap](https://github.com/OpenDroneMap/ODM)**  
  Leading open-source photogrammetry toolkit for processing drone images into maps, point clouds, and 3D models used on construction sites.

- **[fVDB Reality Capture](https://github.com/openvdb/fvdb-reality-capture)**  
  Open reality-capture toolbox for reconstruction, meshes, point clouds, and large-scale visual data processing.

- **[Computer vision construction MVPs (e.g. Obra)](https://github.com/)**  
  Open prototypes using YOLO pose/tracking for worker activity analysis, motion scoring, and site video insights.

- **[WebODM / NodeODM](https://github.com/OpenDroneMap/WebODM)**  
  Open-source web interface and processing nodes around OpenDroneMap for team drone mapping workflows.

- **[OpenBIM / IFC comparison tools](https://github.com/buildingSMART)**  
  Open standards and community tools for comparing design models (IFC) with captured as-built data.

- **[Point cloud open processing (PDAL, CloudCompare)](https://github.com/PDAL/PDAL)**  
  Open libraries and applications for cleaning, classifying, and analyzing LiDAR and photogrammetry point clouds.

- **[360° and panoramic open viewers](https://github.com/)**  
  Community viewers and stitching tools for site walk imagery used in progress documentation.

- **[Schedule vs progress open dashboards](https://github.com/)**  
  Experimental notebooks linking capture-derived quantities to schedules for simple variance views.

- **[Safety and PPE open detection models](https://github.com/)**  
  Computer vision models and datasets for hard hats, vests, and basic site safety analytics experiments.

- **[Documentation and open reality-capture playbooks](https://www.opendronemap.org/)**  
  Guides for drone mapping, photogrammetry, and integrating open capture into construction workflows.

### Additional Strong Open-Source Options
- Processing site drone flights with **OpenDroneMap** / WebODM for orthomosaics and 3D models.
- Experimenting with **YOLO-based** worker and activity tracking on site video.
- Comparing point clouds or meshes to BIM using open IFC and geometry tools.
- Accepting that automated trade-level progress percentages, continuous 360° AI analysis, design vs as-built at scale, and enterprise multi-project analytics still require commercial platforms (Buildots, Doxel, OpenSpace, DroneDeploy, Avvir, Disperse, etc.).
- Focusing open-source efforts on data ownership of captures, research, and reducing vendor lock-in on the mapping layer.

**Frameworks for building custom systems**: Capture with drones/360 cameras → process with OpenDroneMap or open CV pipelines → compare to BIM/schedule in open tools → report in dashboards. Suitable for innovation teams and smaller projects. Large GCs typically deploy commercial site analytics for reliable, trade-level progress intelligence.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Site analytics influence schedule, safety, and payment decisions. Open-source tools require validation before production use. This list is not construction or safety advice.

---
**Made for construction technologists, VDC teams, and open reality-capture advocates.**
Let's keep site progress objective, visual, and as open as practical.
