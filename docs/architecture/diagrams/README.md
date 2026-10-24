# MedPredict architecture diagrams

System context, use cases and preliminary components are the three required architecture views. This bundle was copied without changing its image or editable XML bytes from the project frontend architecture sources on 24 October 2026. It describes the overall local M2 integration and planned application modules, rather than asserting that every component is available in each repository.

These are application-integration diagrams for M2. The newer M1 benchmark is offline only; M1 has no released form/API/ONNX provider, and M3 forecast training remains blocked by source provenance.

The unchanged diagrams are dated 21 October 2026. Labels such as “implemented backend” describe the retained local M2 integration, not the current remote backend main. M1/M3 plan labels and the name `MedPredicts/ml` preserve that historical application snapshot; the repository README records the later offline M1 status. This publication contains documentation only, without the training source, experiment reports or model bundle.

| Diagram | Preview | Editable diagrams.net source |
|---|---|---|
| System context | [context.png](context.png) | [context.drawio](context.drawio) |
| Use cases | [use-cases.png](use-cases.png) | [use-cases.drawio](use-cases.drawio) |
| Components | [components.png](components.png) | [components.drawio](components.drawio) |

![System context](context.png)

Open the uncompressed `.drawio` XML in a compatible diagrams.net editor. After changing nodes, labels or links, export a new PNG and review it for consistency and readability. A preview does not replace the editable source. The diagrams do not establish clinical validity or supervisor approval.

[Project documentation](https://github.com/MedPredicts/documentation#readme) · [Repository README](../../../README.md)
