# ProcureMate

### Camera-assisted inventory and procurement

[Product website](https://www.procuremateai.com) · [Back to my profile](https://github.com/Boat1x)

**Role:** Co-founder & CTO  
**Source:** Private commercial codebase

## The problem

Keeping stock counts useful takes more than recognizing an object in a picture. Supplies move throughout the day, a camera can miss context, and an incorrect count can lead to a poor purchasing decision. ProcureMate connects observations from a shelf to an inventory workflow that a person can review.

## What I work on

My work spans product engineering, camera and computer vision workflows, and AI integrations. The application brings inventory, proposed changes, reorder alerts, and purchasing information into one place.

The public product supports monitoring a selected shelf area through a connected network camera. Continuous video is processed on the facility computer; short clips of a detected shelf action can go to the cloud for product identification. Proposed inventory changes pass through confidence and review gates. Manual shelf-photo scans provide another way to capture inventory information.

## Engineering themes

| Theme | Why it matters |
| --- | --- |
| **Useful evidence** | A proposed inventory change should have enough context for a person to understand and review it. |
| **Uncertainty handling** | Camera angle, lighting, occlusion, and similar-looking products affect what the system can infer. Ambiguous observations need a review path. |
| **Local and cloud processing** | Continuous monitoring and cloud identification have different connectivity and privacy requirements. |
| **Product integration** | An identified item is useful when it connects to counts, alerts, and a clear next action in the application. |
| **Access boundaries** | Inventory and administrative workflows need appropriate identity and access controls. |

## What to explore publicly

- [How the product works](https://www.procuremateai.com): the camera, review, inventory, and procurement workflows.
- [Security overview](https://www.procuremateai.com/security): the product’s public security information.
- [Privacy policy](https://www.procuremateai.com/privacy): the published data-handling policy.

