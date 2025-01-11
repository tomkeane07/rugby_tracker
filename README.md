# rugby_tracker

This was developed for a MSc thesis in Artificial Intelligence at the University of Limerick in 2022.
It received above a 90% grade and was awarded a 1st class honours overall.

[Here's a copy of my thesis, describing what the application does, and how.](./MScAI_Thesis_TS_20214537_Tom_Keane.pdf)


[And here's a copy of a more concise presentation on the subject.](./Presentation_Rugby_Field_Registration.pptx.pdf)


![Rugby Tracker GIF](./rugby-tracker-example-output.gif)


# Abstract
Sport field registration (SFR) and projection to a template field map can provide unique insights
to supplement sport analytics and coaching. SFR and projection have been utilized to various
degrees across different sports, including football, American football, basketball, and ice-hockey.
The challenges imposed on SFR differ in scope and qualitatively across and within sports due to
variations in pitch dimensions, field markings, application of camera pan & zoom, among others.
This thesis proposes a sport field registration model based on Canny edge detection and
Hough line transformations of a rugby broadcast footage, and then contextual semantic rugby
field line classification. Classified lines are used to provide a homography matrix that projects
player positions to a template field map. Player positions are provided prior to the homography
transformation by an Ultralytics YOLOv5 pedestrian detector which is run on each broadcast
frame.
