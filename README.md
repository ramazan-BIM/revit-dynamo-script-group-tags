# revit-dynamo-script-group-tags
Dynamo script for Revit that automatically aligns tags with identical displayed values to improve drawing readability and reduce manual annotation work.

A simple Dynamo script that automatically aligns tags with identical displayed text in Revit.

🎯 What it does

When working in Revit, tags with the same value often end up scattered and need manual alignment to keep drawings clean.

This script fixes that by:

Taking any selection in Revit
Automatically filtering only tags
Checking their displayed text values
Finding tags with matching text
Moving and aligning them together for a cleaner drawing layout

⚙️ How to use
Select elements in your Revit view (no need to filter tags manually)
Run the Dynamo script (.dyn file)
The script will:
Extract tags from selection
Group tags with identical displayed values
Align them together automatically

📹 Demo

See demo.mp4 for a quick example of how it works.

💡 Notes
You can select anything — the script will only process tags
Focuses on displayed tag text
Safe to run multiple times in a view
🚀 Purpose

Built to reduce repetitive manual tag alignment and speed up shop drawing preparation in Revit workflows.
