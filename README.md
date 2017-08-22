Simple MediaPlayer Sample
=========================

This sample demonstrates the use of [`MediaPlayer`](https://developer.android.com/reference/android/media/MediaPlayer.html).
Here are some important things this sample highlights:

- Media playback position and duration are synchronized with a `Seekbar` in the UI.
- If the user manually changes the `Seekbar` position the `MediaPlayer` playback
  position is adjusted accordingly.
- State machine transitions for `MediaPlayer` are displayed in the UI.
- MP3 files are loaded from the `raw/res/` folder (no streaming over network).

The following articles describe what this sample does in detail:

1. [MediaPlayer introduction](https://medium.com/@nazmul/building-a-simple-audio-app-in-android-part-1-3-c14d1a66e0f1)
2. [Buiding the app](https://medium.com/@nazmul/building-a-simple-audio-app-in-android-part-2-3-a514f6224b83)
3. [Synchronizing with the SeekBar](https://medium.com/@nazmul/building-a-simple-audio-app-in-android-part-3-3-ead4a0e10673)

Screenshots
===========

<img src="https://raw.githubusercontent.com/googlesamples/android-SimpleMediaPlayer/master/screenshots/screenshots.gif" width="50%" height="50%">

License
-------

Copyright 2017 Google Inc. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
