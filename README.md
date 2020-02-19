# Presto Vision Analysis

### Description

This interactive GUI was created to make object analysis more efficient for the team as well as the consumer. This tool allows engineers to view the state of the environment during specified timeframes, as well as look for trends in guest/staff behavior as well as to QA the detection and tracking capabilities of Presto Vision. 

## Repository Structure

    builders/                     # builds images for GUI canvas
        canvas_builder.py
    images/                       # images created and plotted on GUI
          activity.png
          forwardbutton.png
          kde.png
          pausebutton.png
          playbutton.png
          rewindbutton.png
    managers/                     # builds GUI and organizes database information
          data_manager.py
          ui_manager.py
          widget_manager.py
    models/                       # creates object summaries from database
        object_summary.py
    threads/                      # accesses database
        db_service.py
