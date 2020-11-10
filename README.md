# EEG-alpha-waves-BCI
[Data source](https://www.kaggle.com/latimerb/eeg-leftright)

This data was created by Benjamin Latimer. "This is a time series of EEG data I gathered on a 28 y/o male (myself)."

## Context
My goal is to eventually create a brain-computer interface. This data set was made to see if it is possible to classify whether my eyes were open or not. It is well known that the eyes closed condition generates alpha waves at 8-12 Hz, which we also see in this recording.

## Content
There are four channels, two on my frontal lobe and two on my temporal lobe. There are also accelerometer channels that show the position of the small EEG board. The first 30 seconds (from 12:52:31.069 to 12:53:00.000) were for calibration. Thereafter, every 30 seconds consisted of eyes open/shut for a total of 5 of each condition.

## Protocol
The subject was in two states during the experiment; their eyes were either open or closed.
Eyes closed in these durations (unit: second): 60-90, 120-150, 180-210, 240-270, 300-330, 360-390, 420-450, 480-510, 540-570, 600-630.
Eyes open otherwise.
