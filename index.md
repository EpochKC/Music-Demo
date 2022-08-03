<script src="https://cdn.jsdelivr.net/combine/npm/tone@14.7.58,npm/@magenta/music@1.23.1/es6/core.js,npm/focus-visible@5,npm/html-midi-player@1.4.0"></script>

<midi-player
  src="https://magenta.github.io/magenta-js/music/demos/melody.mid"
  sound-font visualizer="#myVisualizer">
</midi-player>
<midi-visualizer type="piano-roll" id="myVisualizer"></midi-visualizer>

<midi-player
  src="https://github.com/EpochKC/Music-Demo/blob/main/A_0727/get_0.mid"
  sound-font visualizer="#myPianoRollVisualizer">
</midi-player>

<midi-visualizer type="piano-roll" id="myPianoRollVisualizer" 
  src="https://github.com/EpochKC/Music-Demo/blob/main/A_0727/get_0.mid">
</midi-visualizer>

<midi-visualizer type="staff" id="myStaffVisualizer" 
  src="https://github.com/EpochKC/Music-Demo/blob/main/A_0727/get_0.mid">
</midi-visualizer>
