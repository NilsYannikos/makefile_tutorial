tasty_stuff := cookie cake pancake waffle muffin

all: $(tasty_stuff)
	echo "I just made this tasty food: " $(tasty_stuff)

all_togo: $(tasty_stuff)
	mkdir food_box
	mv cookie food_box/cookie
	mv cake food_box/cake
	mv pancake food_box/pancake
	mv waffle food_box/waffle
	mv muffin food_box/muffin

cookie:
	touch cookie
cake:
	touch cake
pancake:
	touch pancake
waffle:
	touch waffle
muffin:
	touch muffin


eat:
	rm -f $(tasty_stuff)
	rm -rf food_box
	echo "oh that was so tasty..."