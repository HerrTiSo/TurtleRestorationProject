# Turtle Restoration Project (TRP)

> *"Ye think ye know the lands o' Azeroth, do ye? There's much yet to discover, if yer willing to seek it."* – Brann Bronzebeard

The **Turtle Restoration Project** (TRP) enhances the world maps of World of Warcraft’s classic era (version 1.12.1) through machine learning upscaling, tailored specifically for [**Turtle WoW**](https://turtle-wow.org). Created to complement the server’s fan-made expansion, **Mysteries of Azeroth**, TRP aligns with the server’s mission to deepen players’ connection to the **Vanilla WoW** world, capturing Azeroth’s timeless sense of adventure.

At higher resolutions, the original Vanilla maps appear blurry and lack detail. TRP addresses this by doubling the in-game resolution of map files, while effectively increasing visual detail up to four times. The result is a sharper, more immersive map experience that enhances exploration while preserving Azeroth’s iconic charm.

**Note:** While TRP aims for high-resolution quality, the limitations of the old WoW engine require careful adjustments to avoid crashes or instability. As a result, the final map quality may not fully match the resolution of current retail WoW maps but should come impressively close.

TRP is built in a modular way, following a three-phase approach for each map:

1. **Upscaling and Fixing Major Errors**: Initial upscaling of the map and addressing any prominent errors that may arise.
2. **Refining Labels**: Adjusting and improving labels, such as city names and region titles, to ensure clarity and alignment.
3. **Enhancing Visual Details**: Adding final touches to enhance other design elements for a polished, immersive look.

Starting with the major cities, each map requires considerable time and effort as I carefully work through these stages.

In the future, TRP may expand to other private servers under the name **Azeroth Restoration Project**, bringing the same visual upgrades to the broader WoW classic community.

---

## Project Progress

Below is an overview of the current progress on TRP. Each zone goes through three stages: **Upscaling**, **Relabeling**, and **Enhancement**. The checkmark indicates completion of that stage for each zone.

| Zone                     | Upscaled | Relabelled | Enhanced |
|--------------------------|----------|------------|----------|
| World Overview           | ✅        |            |          |
| Eastern Kingdoms Overview | ✅        |            |          |
| Kalimdor Overview        | ✅        |            |          |
| Capitals                 | ✅        |            |          |
| Durotar                  | In Progress        |            |          |
| Elwynn Forest            | In Progress        |            |          |
| ...                      |          |            |          |

---

## Known Issues

Below is a list of known issues currently affecting the Turtle Restoration Project. Each issue includes a brief description, status, and relevant notes. This section will be updated as fixes or workarounds are implemented. If you come across other issues, please report them by opening an issue on GitHub or posting in the forums.

| Issue                      | Description                                                                 | Status           | Notes                                     |
|----------------------------|-----------------------------------------------------------------------------|------------------|-------------------------------------------|
| Overlapping Alpha Borders  | Borders between explored and unexplored areas have overlapping alpha channels, resulting in a checkerboard effect. | Acknowledged     | Investigating solutions to improve visuals. |
| Label Font Glitches        | Some city and region labels appear distorted after ML upscaling.            | Scheduled for Phase 2 | Requires manual relabeling.               |
| Blurry Zoom Levels         | When using the Magnify add-on, certain zoom levels show reduced sharpness.  | Investigating    | Likely due to engine limitations.         |


---


For more information or to join the discussion, please visit the [GitHub Repository](https://github.com/HerrTiSo/TurtleRestorationProject) and [Turtle Forum](https://exampleforum.com).

## Rediscover Azeroth with the Turtle Restoration Project—one map at a time!
