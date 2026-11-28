# 3D-Visor-PRO

3D Visor PRO is a Windows 10/11 desktop viewer for CAD, 3D, mesh, and eDrawings files. It provides quick file inspection, measurement tools, assembly visualization, and optional Windows file associations.

During installation, choose whether to install:

- **For me only** — no administrator permissions required.
- **For all users** — requires administrator permissions.

The installer creates a Start Menu shortcut and an entry in **Installed Apps** for uninstallation. When removed, it also clears any file associations created by 3D Visor PRO.

## Open supported files with 3D Visor PRO

Open **Settings → File Types** to enable or disable file associations individually, either for the current user or for all users on the PC.

Supported extensions include:

```text
.step  .stp  .iges  .igs  .brep
.sldprt  .sldasm  .slddrw
.easm  .eprt  .edrw
.stl  .3mf  .obj  .ply  .glb  .gltf
.epub
```

If another application was previously selected through Windows’ **Open with** menu, Windows may ask for confirmation. 3D Visor PRO will open the appropriate Windows Settings page to complete the change.

## Measurement tools

Select **Measure**, then click vertices, edges, faces, or points.

Available selection modes:

- Auto
- Vertex
- Edge
- Face
- Point

Selecting two elements displays their distance. When two edges or faces are not parallel, the viewer also displays their inclination angle.

## Move assembly parts

Select **Move** to reposition or rotate parts within an assembly view.

For safety, the application asks for confirmation before enabling this feature. Changes affect only the current visual view: the original file is never modified. Select **Reset All** to restore every part to its original position.

## eDrawings support

eDrawings files are supported:

```text
.easm  .eprt  .edrw
```

They are read using the open-source `edrawings-kit` library, licensed under Apache License 2.0. See the `licenses` folder for attribution and license details.

eDrawings support is available in the Windows application only and is not included in the web preview.
