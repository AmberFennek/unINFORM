"Dirty hands, clean hands!" by Test Subject

The story description is "This test features you, a clean napkin, a dusty tree and your hands.[line break]You can touch X, rub X, wipe X, rub X on Y and wipe X on Y.[line break]No message is given if no state change takes place.[line break][line break]"

The story creation year is 2016. 

When play begins:
		 say "[story description]"

Forest is a room. "You are in a forest. Surrounding you are thick dark trees that create a canopy above you." 

A thing can be dusty or clean.  A thing is usually clean.

A dusty tree is in Forest. "The nearest tree looks dusty." It is fixed in place and dusty. A description is "If you rub your hands on this tree, you will become dusty."

The player carries a napkin. It is clean. A description of napkin is "This [napkin] [are] [if napkin is dusty]dusty[else]clean[end if]."

hands are a kind of thing. hands are part of every person. The description of hands is usually "You see two, one at the end of each arm." Hands are plural-named. 

A description of your hands is "These hands are [if player is dusty]dusty[else]clean[end if]."

Rubbing on is an action applying to one thing and one visible thing. Understand "rub [something] on [something]" as rubbing on.

Instead of rubbing on something fixed in place:
	say "That can't be moved."

Check rubbing:
	try touching noun instead.

Check rubbing on:
	if the noun is your hands or the noun is the player:
		try touching the second noun instead;
	otherwise:
		if the noun is a napkin and the noun is clean and the second noun is a tree:
			Now the napkin is dusty;
			say "Dust from [second noun] is transfered to [noun].".
		
Instead of touching tree:
	if the player is clean:
		say "Dust from the tree is transfered to your hands.";
		Now the player is dusty.
	
Instead of touching napkin:
	if the player is clean and the napkin is dusty:
		say "Dust from [napkin] is is transfered to your hands.";
		Now the player is dusty;
	if the player is dusty and the napkin is clean:
		say "Dust from your hands is transfered to [napkin].";
		Now the player is clean;
		Now the napkin is dusty.
