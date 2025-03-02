<h2> This repository is meant to log, control, and automate switching between power sources(grid/solar) during the frequent, and extended power cuts I experience.</h2>
<ul> 
  <li>The main idea is to control the refrigerator power sources according to the availability of solar power/AC grid to protect the battery from deep discharge and the refrigerator motor from surge current failures. (surge current happens when the inverter relay fails to seamlessly switch between the two power sources) </li>
  <li>Inverter provided power is dynamic according to cloud cover and total sun hours.</li>
  <li>Total AC grid power availability is logged to a csv file.</h3> 
  <li>It assumes that a homeassistant core container is up and running using the formal Docker command provided by homeassistant documentation: https://www.home-assistant.io/installation/linux

. </li>
  <li>Files should be placed in /config directory inside the container, place the .yaml files directory in place of -v /PATH_TO_YOUR_CONFIG:/config in the docker command.</li>
</ul>
<ul>
  <li> for more information about Home Assistant: https://www.home-assistant.io/</li>
  <li>for more information about sonoffLAN(An integration Used to control sonoff smart devices through Home Assistant): https://github.com/AlexxIT/SonoffLAN</li>
</ul>


