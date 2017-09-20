Robotour - robotika.cz outdoor delivery challenge

version 6 (2018-01-31)

The Goal of the contest

The objective of the Robotour contest is to encourage development of robots
capable of transporting you to work in the morning or to deliver the building
material you have just purchased in an online shop. The path to this goal is
neither easy nor short, but we believe that the outcome is worth it.

Rules

Task

The task for the robots is to pickup payload in loading area, deliver it to
the destination for unloading and return back to service area. This has to be
realized within 1 hour time limit and the destination can be
as far as 1km. Robots must be fully autonomous, not leave the road
and choose correct path on junctions. The place of start and destination will
be the same for all robots.

Map

The robots can only use Open Street Map. The key concept of this map is its
verifiability.  Anything that is verifiable and is described in map features
can be used by the teams to update the map of the contest area. Note, that Open
Street Map is primarily used for people, and certain rules have to be
respected.

Robots

Team can deploy only one robot. Every robot must have EMERGENCY STOP button,
which stops its motion. The button must be easily accessible, red and must be
fixed part of the robot (Big Red Switch), so it could be used in case of
danger. The minimum size of the switch is defined by an inscribed circle with
diameter of 2cm. The team must show that it is easy to manipulate with the
robot - two people must be able to carry it several tens of meters. There is
also minimal size - robot has to be able to carry full 5l beer barrel, which
should be easy to load and unload.

Leaving the road

The robots are expected to stay “on the road” which means to stay on the paved
passage ways. If any robot leaves the road, the trial ends. The team has to
take care of their robot and remove it immediately.  

Obstacles 

There could be
obstacles on the road. Besides natural obstacles like benches there could be
also artificial obstacles. A typical (artificial) obstacle is for example a
figurant, a banana paper box or other robot. Robots may not touch an obstacle.
Contact with an obstacle means end of the trial. The robot may stop in front of
the obstacle and visually or acoustically give notice.  Note, that the robot
has to detect, that the obstacle is no longer present.

Robots Interaction

The cases where a faster robot catches up a slower one won't be explicitly
handled. The faster robot can handle the slower robot as an obstacle, i.e.
avoid it or wait until the obstacle disappears. In general the road rules
will be respected: right of way, avoidance to the right, passing on the left.

Autonomous, semiautonomous and service areas

The competition area is described by polygon and it is called "Autonomous
Area". The robots can move in this area in autonomous mode only. In the case of
a collision, leaving the road or due to some other issues the contestants have
to remove the robot from the Autonomous Area. The complementary space, called
"Service Area", is the where all the maintenance and programming will take
place. There is also a "Semiautonomous Area" between autonomous and
service area. In the semiautonomous area the robot has to navigate autonomously
but in a case of problem the team can take the robot back to service area.

Start

All robots will start simultaneously on arbitrary park road within the service
area. In the very minute of task announcement (position of loading and
unloading area) the robots can start. The coordinates will be defined via QR code.
Contestants pass the entry to their robot in the service area, but organizers
will enter the next destination in the loading and unloading zone.

Blocking traffic

Due to the crowds of robots in potential narrow roads it is necessary to deal
with traffic blockage. Every team can in any time sue a robot of another team
that is blocking road. From that moment sued robot has one minute to leave an
area defined by +/- one meter from its current position. If the robot fails to
leave this area it will be stopped and removed from the road. Otherwise the
contest continues and suing team gets warning for false judge. If this is for
the 3rd time the robot of suing team is stopped and removed from the road.

Reaching goal

The robot has to indicate when the goal is reached (in both loading and
unloading area), for example via sound signal. The judge marks that position
and robot autonomously navigate to the next goal without operator interaction.
The robot has to be able to recognize if the loading and unloading operation
is completed.

Score

The team whose robot manage best to proceed along the route wins. Only reaching
the goals positions is awarded (10 points for reaching the load area and 10 points
for reaching the unload area). Finally 10 points can be gained for return to
service area after task completion. In total the team can get maximum of 30 points
per run.

There is also a penalty 5 points if robot leaves the road, collides with an obstacle,
or must be stopped by emergency STOP button. The robot can terminate its attempt
any time, by stopping and indicating (flashing lights like for cars recommended)
that it is not capable to safely finish the task and to return to service area.
In this case no penalty is enforced, but given round is over for this particular
robot. The score shall not be negative number, so each run will be evaluated as
max(0, result).

Organization

The contest will consist of 4+1 runs. The start and destination will be
different for every trial. The announcement of destination defines the start.
The speed of the robots is not important (actually the speed limit is 2.5m/s).
All points gained during all trials will be summed together. The trial starts
at a specified time and ends after 1 hour. Each team has to arrange for one
person familiar with the rules that will be part of the referee team during the
competition.

Homologation

A team can participate in the contest if it is able to score at least one
point.  Necessary condition is the ability to travel 10 meters long route
fragment without collision with an obstacle. The manual loading
will be tested as well as the functionality of the EMERGENCY STOP. Usage of
liquids, corrosive, pyrotechnic material and live beings is strictly
prohibited. Every robot has to be accompanied by a team member, older 18 years,
who is fully responsible for the robot behavior.

Technical documentation

Every team has to provide basic technical documentation about their robot (for
presentations, general public and journalists). Three winning teams will be
asked for more detail description for website presentation and easier entry of
novices in the next year.


APPENDIX

QR Code for `lat=49.2114278 lon=18.7445554`

![QR Code](qrcode.svg)

(generated by https://github.com/mnooner256/pyqrcode)
