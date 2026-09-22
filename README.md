# Parikshit Racing | FKDC 2026

**Team:** Parikshit Racing, SAE Collegiate Club of MNNIT
**Project:** 2026 Formula KART Driving Challenge (FKDC)

This repository serves as the central data hub for the 2026 vehicle. It organizes CAD models, simulations, control code, and official documentation across isolated department directories.

## Repository Structure

The workspace includes the following primary directories:

* **`Design`**: Main chassis framing and aerodynamic CAD and analysis files.
* **`Documentation`**: Rulebooks, FMEA reports, BOMs, and design reports.
* **`Electrical_and_Electronics`**: Wiring diagrams, battery mounting, kill switch circuits, and basic sensor code.
* **`Steering`**: Steering column, tie rods, pitman arm assemblies, and turning geometry analysis.
* **`Transmission`**: Chain drive, sprockets, clutch/motor mount CAD, and power transfer data.
* **`Wheels_and_Braking`**: Hubs, rotors, calipers, pedal boxes, and braking distance analysis.
* **`README.md`**: Project overview and repository instructions.

## File Upload Instructions & Workflow

To maintain clean assemblies and prevent data loss across multidisciplinary teams, all members must adhere to the following workflow.

### How to Upload
1. **Branching:** Never push directly to the `main` branch. Always create a new branch for your current task (e.g., `steering-geometry-update`).
2. **Uploading via Web:** For standard documents or minor code tweaks, navigate to your specific department folder, click **Add file** > **Upload files**, drop your files, and commit them to your new branch.
3. **Uploading via Git (Recommended for CAD/Code):** Clone the repository locally, save your work in the respective local folders, commit the changes to your branch, and push to GitHub.
4. **Pull Requests (PR):** Open a Pull Request to merge your branch into `main`. Request a review from your department lead before merging.

### Strict Upload Rules (What NOT to Do)
* **Never upload broken CAD references:** Do not upload isolated part files (`.sldprt`) if they are part of a larger assembly without uploading the updated assembly file (`.sldasm`). Use your CAD software's Pack and Go feature to capture all dependencies.
* **Never bypass the folder structure:** Do not drop files into the root directory. Every file must be placed inside its specific department and subfolder (CAD or Analysis).
* **Never overwrite without pulling:** Always fetch and pull the most recent version of the repository to your local machine before beginning work to prevent version conflicts and overwriting a teammate's progress.

## Team Leadership

* **Captain:** Srikara Badarinath M
* **Manager:** Kartik Shrivastava
* **Design Lead:** Samruddha Musale
* **Electrical & Electronics Lead:** Mritunjay Rai
* **Chassis Lead:** Aviral Maurya
* **Transmission Lead:** Shrey Gupta
* **Wheels & Braking Lead:** Vishal Soni
* **Steering Lead:** Kshitiz Ratna
