## Custom Ionization Source Interface for Orbitrap Exploris 120

A custom **mechanical mounting and positioning interface** developed to integrate external ionization sources with a **Thermo Scientific Orbitrap Exploris 120 mass spectrometer**.

The interface was initially designed for a **dielectric barrier discharge (DBD) ionization source**, but its modular design allows adaptation to other devices and experimental configurations.

The objective was to develop a robust, removable interface with **fine XYZ positioning** and coarse adjustment to move the ionization source toward or away from the mass spectrometer inlet.

The project involved **3D CAD modeling, PETG/PLA 3D printing, mechanical component selection, lathe machining, and mechanical assembly**.

The interface was designed and assembled by me, combining original mechanical components with modified open-source linear stages.

**Complete mounting system:**

<img width="1173" height="783" alt="IMG_4937" src="https://github.com/user-attachments/assets/12554152-d666-4a9d-9768-1fba4775de52" />

<br>
<br>

## Mechanical Design

The system was designed to provide rigid attachment to the Orbitrap while allowing precise positioning of the DBD source (or another apparatus).

Its main components include:

- **Custom aluminum mounting pins:** manufactured on a lathe to fit the Orbitrap mounting points.
- **20 × 20 × 300 mm aluminum extrusion:** provides coarse positioning toward or away from the instrument inlet.
- **V-wheel sliding carriage:** moves along the extrusion using four polymer-coated wheels.
- **Three 3D-printed linear stages:** provide independent fine XYZ positioning.
- **Custom adapter and locking mechanism:** connect the carriage to the linear stages and secure its position.
- **PETG structural components:** custom-designed and 3D-printed for the assembly.

Most structural components were modeled in CAD and fabricated using PETG/PLA.

### Orbitrap Mounting and Machined Components

The mounting system uses custom **7 mm diameter aluminum pins**, manufactured on a lathe to provide a secure mechanical connection to the Orbitrap.

Each main pin includes a threaded hole for a perpendicular modified **M4 screw**.

These components were designed to reproduce the required mounting geometry while minimizing mechanical play.

**Machined aluminum pins and dimensional drawing:**

<img width="1463" height="821" alt="image" src="https://github.com/user-attachments/assets/d2e698ee-c9ed-4685-b57a-ae9131b9bbef" />

<br>
<br>

**Lathe machining and threaded pin fabrication:**

<table>
  <tr>
    <td width="50%">
      <video src="https://github.com/user-attachments/assets/bce30eeb-1a35-4457-ae7a-f615be198c33" width="300" controls></video>
    </td>
    <td width="50%">
      <video src="https://github.com/user-attachments/assets/1fb1724b-5824-420c-b7f0-d0457aff4bad" width="300" controls></video>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%">
      <img width="1067" height="858" alt="image" src="https://github.com/user-attachments/assets/76d514f9-a91b-46c7-b517-cf53a1eaaedd" />
    <td width="50%">
     <video src="https://github.com/user-attachments/assets/7ba5b432-4f87-427a-80d8-5bb20058c09a" width="300" controls></video>    
    </td>
    </td>
  </tr>
</table>

<br>
<br>

### Coarse Positioning Mechanism

A **300 mm long, 20 × 20 mm aluminum extrusion** supports a sliding V-wheel carriage, allowing the complete DBD positioning assembly to move toward or away from the Orbitrap inlet.

A custom 3D-printed adapter connects the carriage to the first linear stage. An integrated locking screw secures the carriage at the selected position.

The aluminum extrusion is attached to the main support using **M5 T-slot nuts and M5 × 16 mm screws**, while the printed structural components are assembled using **M5 × 60 mm screws**.

**Sliding carriage, adapter, and locking mechanism:**

<table>
  <tr>
    <td width="50%">
      <video src="https://github.com/user-attachments/assets/37c48658-ac9f-43d3-a3ce-4f4b1fd1d2f7" width="300" controls></video>
    </td>
    <td width="50%">
     <video src="https://github.com/user-attachments/assets/a2657580-26c9-4cfe-a0ec-463d202a162e" width="300" controls></video> 
    </td>
  </tr>
</table>

<br>
<br>

## Fine XYZ Positioning

Three 3D-printed linear stages were assembled to provide independent fine adjustment along the **X, Y, and Z axes**.

The design was adapted from the open-source [Printed Linear Stage by Remi-Rafael](https://www.thingiverse.com/thing:6650149).

I introduced several mechanical modifications:

- **70 × 70 mm dimensions** to accommodate the mounting assembly.
- **Bidirectional screw-driven movement**, replacing the original spring-return mechanism. An M3 × 50 mm adjustment screw pushes and pulls the moving platform.
- **2.5 mm guide rods** to support and guide the sliding components.

These modifications resulted in a compact positioning system suitable for aligning the DBD source with the Orbitrap inlet.

**Modified linear stage CAD model and printed components:**

<table>
  <tr>
    <td width="33.33%">
      <img width="1275" height="851" alt="image" src="https://github.com/user-attachments/assets/52c2fbbd-d9b8-4f01-a396-1d6c319034f7" />
    </td>
    <td width="33.33%">
      <img width="1061" height="744" alt="image" src="https://github.com/user-attachments/assets/627a38cb-bcbd-4d0f-a529-97eadfcda768" />
    </td>
    <td width="33.33%">
      <img width="1313" height="1022" alt="IMG_4906" src="https://github.com/user-attachments/assets/d82f31de-eae2-4a66-a40a-d004afd64dd0" />
    </td>
  </tr>
</table>

<br>
<br>

**Printable Position Scale**

I also designed a miniature measurement scale (-20 to +20 mm) to be attached to the 3D-printed linear stages, providing a visual reference for positioning adjustments.

The scale can be printed on regular paper using 100% scale (actual size) in the printer settings to preserve the correct dimensions.

For better durability, transparent adhesive tape can be applied over the printed surface to protect it from wear. Double-sided adhesive tape can then be applied to the back to attach the scale to the linear stage, as shown in the photo below.

Printable scale: **[Download PDF](STL-files/Linear-stage/Label-linear-stage.pdf)**

<br> 

**Complete XYZ positioning assembly:**

<table>
  <tr>
    <td width="50%">
      <img width="952" height="856" alt="image" src="https://github.com/user-attachments/assets/02937fd1-40ed-4464-a673-676671230c2f" />
    </td>
    <td width="50%">
      <img width="1301" height="1272" alt="IMG_5212" src="https://github.com/user-attachments/assets/98893e27-4ef0-499a-baea-86cc4dc8cefd" />
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%">
       <video src="https://github.com/user-attachments/assets/1f58583a-cb8b-42a4-9a5a-2a5376ecaa07" width="300" controls></video>
    </td>
    <td width="50%">
      <video src="https://github.com/user-attachments/assets/e6fef60a-765d-4f7b-b6e1-c23f78c1be59" width="300" controls></video>
   </td>
  </tr>
</table>

<br>
<br>

## Integration with the Orbitrap Exploris 120

The mounting system was developed to accommodate a lab-made DBD plasma device powered by one of our custom high-voltage supplies.

Related project: **[High-Voltage Power Supplies for DBD Plasma](https://github.com/gilberto-coelho/High-Voltage-Power-Supplies-for-DBD-Plasma)**

The design also considered the mechanical interface used by the commercial **DART ionization source mounting system**, including its attachment geometry and module-presence detection mechanism.

The Orbitrap interface includes a mechanical detection pin and a multipin electrical connector used for module identification. The electrical identification interface will be documented separately.

**Comparison with the commercial stainless-steel DART source support:**

<img width="1460" height="863" alt="IMG_4943" src="https://github.com/user-attachments/assets/28d0415e-f969-45f8-ba3a-0c11fa375531" />

<br>
<br>

## Main Components

| Component | Specification |
|---|---|
| 3D-printed components | PETG |
| Orbitrap mounting pins | Custom lathe-machined aluminum, Ø7 mm |
| Perpendicular mounting pins | Modified M4 screws |
| Structural screws | M5 × 60 mm |
| Aluminum extrusion | Black 20 × 20 mm profile, 300 mm long |
| Sliding carriage | V-wheel linear carriage for 20 × 20 mm aluminum extrusion |
| Extrusion nuts | M5 T-slot nuts |
| Extrusion mounting screws | M5 × 16 mm steel screws, low-profile socket heads |
| Fine positioning | Three modified 70 × 70 mm linear stages |
| Linear stage adjustment screws | M3 × 50 mm |
| Linear guides | Ø2.5 mm rods |
| Threaded inserts | M3 brass inserts |

The assembly combines commercially available mechanical hardware with custom-designed and machined components.

<br>

## 3D Models and Demonstrations

**[STL Files](STL-files/)** — 3D-printable mounting components, adapters, and modified linear stages.

**Complete CAD assembly:**

<table>
  <tr>
    <td width="50%">
      <img width="1274" height="881" alt="image" src="https://github.com/user-attachments/assets/01ffbb2b-50ec-40e9-af77-c699e8e536a2" />
    </td>
    <td width="50%">
      <img width="1257" height="866" alt="image" src="https://github.com/user-attachments/assets/cc68ded1-0a6f-465a-aba5-7e376680cc87" />
    </td>
  </tr>
</table>

<br>
<br>

**Installation on the Orbitrap Exploris 120:**

https://github.com/user-attachments/assets/ee95a935-ca86-435c-801c-68a8f7ad99ae

<br>

## Credits and License

The modified linear stages are based on the original **[Printed Linear Stage](https://www.thingiverse.com/thing:6650149)** designed by **[Remi-Rafael](https://www.thingiverse.com/Remi-Rafael/designs)** and published on Thingiverse.

The original design is licensed under **[Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)**.

My modifications include:

- Resizing the design to 70 × 70 mm.
- Replacing the spring-return mechanism with bidirectional screw-driven movement.
- Incorporating 2.5 mm guide rods.

The modified linear stage files are shared with attribution to the original creator and subject to the non-commercial restrictions of the original license.

All other custom mechanical components were independently designed and fabricated by me.

<br>

## Author

**Gilberto Coelho**

I personally developed the mechanical mounting system, including **CAD modeling, 3D printing, aluminum machining, component selection, assembly, and integration with the Orbitrap Exploris 120**.
