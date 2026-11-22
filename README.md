# 3D humans: a user study (part 2)

A static website (GitHub Pages): for each of five people, a short input video and three 3D reconstructions of the person as
360-degree turntables, shown in a fixed random order and labelled A-C. Participants choose, for each person, the reconstruction that
looks most like the person in the video and press Submit; each answer is sent to a Google Form.

- `index.html`: the page (styles and scripts inline), built by `build.py` from `manifest.json` (and `form.json`, the form's address).
- `videos/<person>/`: the input clip and the turntables (full resolution, previews, posters).
