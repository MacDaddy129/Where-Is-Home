# Where-Is-Home
game ideas / source code

WHERE IS HOME
-------------

PUBLICITY - 
blog
youtube
twitter
instagram
facebook
website
twitch

stranded on a planet

15:00 - every fifteen minutes the game gets harder

every day, a random amount of controls are randomized
	if (keysPressed > 5) {
		playerHealth -= playerHealth * 0.5;
	}
	
if a player doesn't reach a quota (ie. one mission every four in-game days) the game forces them
to complete the mission or at least attempt it

make every single item inspectable or useable no matter how trivial

[PLAYER] finds out they are an alien and must kill father to get home

have a mission function for reusability
	bool mission(int timeInMilis, string name, ...[other param.]) {
		bool isComplete = false;
		
		/.../  //run the mission
		
		return isComplete;
	}
	
