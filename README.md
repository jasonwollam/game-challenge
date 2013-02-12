<h1>Welcome to the Game Challenge!</h1>
<p><strong>WARNING:</srong> The instructions below may be incorrect, I wrote them from memory. I will be updating this tonight with varified info.</p>
<hr />

<h2>Quick start for side scroll platformer:</h2>

<p>After cloning repository and placing files in UDK file structure you will need to edit a config INI file and set game type in the map.</p>

<ol>
  <li>Open \UDKGame\Config\DefaultEngine.ini - Add <strong>+EditPackages=StarterPlatformGame</strong> under [UnrealEd.EditorEngine]</li>
  <li>Start UDK Editor and open the map StarterPlatformMap.udk
    <ul>
      <li>Goto View > World Properties</li>
      <li>Click Game Setting to expand</li>
      <li>From drop down select SCG_GameInfo and save the map</li>
    </ul>
  </li>
  <li>Start UDK Front-end and clone a profile</li>
  <li>Remove any preselected maps and add StarterPlatformMap</li>
  <li>Click start</li>
</ol>
