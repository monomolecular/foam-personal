# Creative Engineering

## Class notes

### Day 1

How to build stuff, and get people to care about it... ***Story-motivated builds***. This is a cool idea which I could encorporate into my organizations product/development process.

What is the motivating problem that directs the build? Necessity is the mother of invention. Start with the challenge you're trying to solve, the build comes second. The glitter bomb went viral because there was a shared understanding of the problem and it resonated with them. The story should have heart... make it personal to me.

Builds fall into three camps:

1. Super Human... I suck at something so I made a machine that could do it.
2. Over Engineering... a rube goldberg machine.
3. Big & Extreme... world's largest something.

Numbers 1 and 2 are probably more appropriate for class.

**Brainstorming**... this first project's going to be ***mechanical*** and the category (constraint) is ***food***. Builds 2 and 3 will be *electrical engineering* and *programming*.

Engineering Design Process:

1. **Brainstorm** - With requirements and constraints, because these give direction and focus. This fourstep process works for any size project.
   1. *Scenes* - idea generation
   2. *Problems* - these should resonate with people
   3. *Solutions*
2. **Research** -
3. **Prototype** -
4. **Final Build** -

Mark brainstormed scenes with food... restaurants, baking at home, making breakfast, grocery shopping, snacking, cooking a meal, pet feeding, and meals for kids.

Then problems...

* grocery shopping
  * Where to find stuff
  * picking produce
    * watermelon knocker - silly, but check the science, why a hollow sound is good. Test it, check the pitch, use an app to check, then taste test. The scientific method could be fun.
* baking at home
  * gathering ingredients
  * cracking an eggs
    * Gravity cracker - Some rube goldberg device which separates the egg somehow.
* breakfast
  * splashing grease
  * milk/cereal soggy
    * Solve the soggy, minimize the milk soak time... giant spoon just in time delivery of cereal and milk (what's the video title and thumbnail)
* cooking a meal
  * cutting vegatables (onions)
    * General - Make it quick, push through a grid.
    * Onion Cutting - Onions could have a good back story, why do you tear up, add a fan on the knife, colder maybe doesn't make your eyes water as much. Science project is fun to add flavor to the story. Liquid nitrogen gets it cold first, etc.
  * measuring ingrediants
* restaurants
  * dropping utensile
    * replacement forks from a forearm mounted wolverine/spiderman device
  * flagging down server (rude?)
    * Something ridiculous, though it's probably too annoying and you'll look like a jerk... so idea rejected.
* snacking
  * efficiency/not lose focus
    * voice activated snackapult and catch a reeses pieces on demand (resonates with Mark)
  * hide the snacks
    * time delay for impulse snacking
* pets
  * feeding process
    * butt disguise when stepping on the feedning mat
  * tourist trap (make it funny)
* meals for kids
  * make it exciting
    * pancake maker with ingrediants, stand-alone system (more exciting if it happens in one action) with limited input to get it started.
  * messy eating

Next, solutions... added above.

1 example... Next step he just did some googling and image searching to get inspired. He licked the dog feeder and ended up on the dog sticking its head through a board to get a wig and a costume on them and then a mechanical hand to feed them.

Stand back and look at the idea/solution board and see if something stands out, downselect:

1. Is it creatively inspiring to you? You need to be stoked.
2. Is there a good story, relatable (good thumbnail and title, like cutting onions).
3. Are there good plot points?
4. How does it tie into your own back story (snack-a-pult).
5. Does it fit the criteria? (mechanical and food are the assignment)

He selected the snack-a-pult. He'd use this in real life.

Talked about problems where the tech solution doesn't exist. There's going to be a piece of tech that will automatically map a space and he'd like to map an ant colony, or space mountain.

Brainstorm, Research, Prototype, Final Build... we just covered Brainstorming.

## My Brainstorming

* **Scenes**
  * Problems
    * Solutions

* **Eating Healthy**
  * Weighing the Food/Calorie Calculation when JulieAnn cooks.
  * Difficulty Deciding What to Eat
  * Difficulty Deciding Who will Cook
* **Making Perfect Eggs**
  * Jammy Eggs - Microwaving is inconsistant (amount of water, size of eggs)
  * Poached Eggs - Hard to keep them from coming apart.
* **Feeding Pets**
  * Cat only eats a little bit at a time. Dog goes and finishes her meal.
    * Cat sensor that opens and allows access to the food just for the cat. Weight sensor on the bowl which lets the dog clean it.
  * Dog stands in odd places to indicate what she wants.
  * Guinea Pig needs fresh greens on a schedule.
* **Food Shopping**
* Amazon Subscribe & Save always gets the timing wrong.
* Forgetting what you have in the pantry and overstocking.
* **Making Bread**
* **Prepare-ahead Meals**
* **Popping Sorghum**
  * Low Success Rate, comes out toasted and mostly unpopped.

**Spit Shine Secure Cat Dish**
A cat feeding contraption that will serve the cat food and protect it from the dog. Ideally it will serve up the cat (her name's Panda) a small portion of her preferred wet food, Fancy Feast seafood pate. The cans are 3, she might eat half that (or less) in one sitting but will sometimes not finish even that amount. The dog (Allie), is always waiting in the wings and will go from a normal clickty clack scamper across the floor to a retracted-nail ninja walk and silently swoop in and scarf down the left-overs before we can stop her. Licking the bowl clean is the highlight of the dog's day, so I don't want to take that away from her. So this device should serve the cat a small amount when she's hungry, and protect the food if she walks away before finishing. If she comes back, it should allow her to finish. Once she's finished, it should call the dog to come and lick the bowl clean (Pavlovian training) so that it's ready for the cats next meal. Then the process repeats.



[Research, Experimentation, & Design](https://monthly.com/mark-rober-engineering/classroom/curriculum/project-1b)

**Requirements:**

* Essential
  * Should not scare the cat
    * Needs to be quiet
    * Needs to move slowely
    * Should not cover the dish on the cats head
  * Sense when the cat is present AND not confuse the dog for the cat.
    1. Tilt switch - Might be simplest to combine this with a "foot plate" that the dog wouldn't step on but the cat would
    2. Mechanical switch - plus step?
    3. Photo interrupter/lazer - based on animal height?
    4. emmitter/receiver - based on animal height?
    5. 1st pressure plate - to sense the cat's weight
       * cat = 11.4 lbs
       * dog = 29.6 lbs
    6. [Grid-EYE Infrared Array Sensor](https://www.digikey.com/en/product-highlight/p/panasonic-electric-works/grid-eye-infrared-array-sensors)
    7. Security camera w/ cat image matching
  * Needs to uncover the dish when the cat is present
    * Stepper motor and pulley - could lift the cover
    * Pneumatic actuator - could lift the cover with a lever arm, or slide the cover over if open on one end. **Ruled out due to noise.**
  * Cover dish if cat is NOT present AND food is left
    * 2nd pressure plate - If the cat's not present, using the first 1st pressure plate then check another pressure plate which weighs the food dish. If triggered reverse the uncovering system above
    * Science experiment - weigh the cat and the dog.
    * Science experiement - weigh the food dish and experiment with how much food is left when the cat is done eating
      * clean/licked = 110g (spit made no difference)
      * dirty = TBD (will take multiple measurements)
  * Leave dish uncovered if cat is done so the dog can clean up
    * That second pressure plate needs to actually weigh the bowl
  * Leave dish uncovered if the bowl is clean and can be refilled
  * Adjustable sensitivity for bowl emptiness
  * Should not scare the dog
    * Probably just means stay open if empty
  * Shouldn't be really big and get in the way
    * Rules out building some sort of box around the dish
* Non-Essential
  * Notify the human when the cat is present, with an empty bowl needing refilling
  * Ability to log the cats meals and report on the results
  * Ability to report on the average time between cat done and bowl licked by dog
  * Ability to open catfood cans
  * Accept a stack of cans to refill from
  * Serve from a new can if the dish is empty
  * Handle cans of varying sizes

Narrowing down design options:

* Meets requirements
* Has a good story
* Maximizes simplicity & minimizes build time
* Works with external constraints
