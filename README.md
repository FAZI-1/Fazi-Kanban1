# FAZI KANBAN BOARD

Static website ready for GitHub and Vercel.

## Deploy
Upload **all files** from this ZIP into the **root** of your GitHub repository (not inside a subfolder). In Vercel, import that repository, select **Other** as framework preset, leave the build command empty, and set output directory to `.` (or leave Vercel static defaults). Deploy.

## Data
Tasks are stored locally in the browser using localStorage. They persist after refresh, but do not sync between browsers/devices. Use Export Backup regularly. Reset Board deletes tasks only after confirmation.
