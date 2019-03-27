“I need some assistance.” Rick peered over the top of his work bench. It wasn’t often that a dame walked
into the lab, and a real looker at that. Beautiful, intelligent women had a way of turning his life into a
burning hell and this one was a potential forest fire in heels. “Damn!” he cussed as he shook his finger,
now blistering from its unfortunate collision with the hot soldering iron. Rick sidled up to her, somewhat
wary. She was a knock-out, that’s for sure; the kind of woman who could make Ingrid Bergman look bad
on her best day and from her demeanor Rick assumed an MIT grad, maybe Stanford. Confident, tall and
slender, she had the longest legs Rick had ever seen. “From her hips all the way down to the floor”, as his
companion, Frankie the lab rat, would say. What could she possibly want from his little lab? “What can I
do you for, er, I mean, what can I do for you?” he stammered. “I’ve got a problem”, she said in a voice so
husky it could pull a dog sled. “I’ve got control issues and I need an expert.” “Expert, eh? I think I know
someone, Miss…Miss…What did you say your name was?” “I didn’t”, she responded. “It’s Miss C.”
Rick furrowed his brow. “Missy? Missy who?” “Just Miss C”, came her curt reply.

Rick looked over his shoulder at his lab partner. “Frankie, we’re going down the hall to visit The Italian.
Finish up the prototype but don’t Bogart that ‘scope ‘cause Louie needs it.” He turned to the dame,
“Follow me”, he said. They walked down the hall in silence until they came to a door with a small red,
white and green flag sticker on it. Rick knocked. The door opened revealing a young man with dark hair
and a five day old beard that was perfectly trimmed around the edges. Inside the office sat a large framed
photo of a Ferrari, some postcards from San Marino and what appeared to be spare parts for some manner
of medieval coffee machine. “Si?” said the young man, one eyebrow raised, looking like a cross between
a GQ model and Mr. Spock.

“Arduino, this is Missy”, said Rick. “Che?” came the young man’s response. “Not Kay, C”, said the
dame. Arduino looked at her and asked, “Not Casey, but who?” She sensed a possible language barrier
and tried to meet him halfway. “Miss C, si?” she said. “Missy C”, nodded Arduino. “No”, she replied,
her exasperation increasing, “Not CC, what am I, a compiler?” Arduino was getting confused now. “Nazi
see what??” he asked, his eyes scanning up and down the hallway. The dame tried a different approach.
“OK, suppose I was your mother’s sister. I’d be aunt C”, she countered. “Yeah, well if you was my
mother’s sister I’d be antsy, too”, added Rick. The dame moved in close to Arduino and almost whispered
through clenched teeth, “Look, just call me Miss C, see?” “Got it!” said Arduino. “Please come in. How
can I help you Miss Seesi?” Rick shook his head as he lowered his gaze to the ground. How had the script
devolved into a bad parody of an Abbott and Costello routine? Puns were more to his liking. Surely he’d
have to Warn her Brothers about this. Of all the labs in all the colleges and universities in the world, why
did she have to walk into his?

“What seems to be the problem, Miss Seesi?” asked Arduino. The dame was beginning to get a headache,
the kind that builds from behind the eyes until it feels like your skull is filled with monkeys playing dodge
ball. She took a deep breath and exhaled slowly. “I’ve got an application that’s in trouble”, she said.
“Trouble,” thought Rick, “yeah, I’ll bet this dame knows all about trouble. It’s part of the package with
these ones, must be in their DNA. Why, if I was a bug she’d be a regular Venus De Flytrap – beautiful
and deadly.” Arduino clasped his hands together and smiled. “Trouble? No trouble! You’ve come to the
10 If you’re not familiar with the 1942 film classic Casablanca starring Humphrey Bogart and Ingrid Bergman, as
well as the film noir genre, it is strongly suggested that you watch the movie and a film noir title before proceeding.
The attitudes expressed here are not necessarily those of the author.

right place. Tell me more about this trouble.” “Well, I’ve got to control a bunch of devices; LEDs,
motors, actuators, the usual crew”, she started, “and I’ve got to obtain some information from the person
running the system, you know the kind, a real operator. Lots of settings; pushbuttons, switches,
potentiometers, the whole megillah. I tell ya, I’m in over my head.”

Arduino walked across the office and nibbled at some biscotti. He turned back to her, the twice-baked
biscuit still at his fingertips, held softly the way an orchestra conductor might balance a baton. “This
application…” he said, his head slightly raised and cocked to one side revealing the beginning of a
knowing smile, “…it needs to be flexible, expandable and inexpensive, too?” He had piqued the dame’s
interest but she couldn’t let it show. “Yes. Yes it does”, she responded coolly. “In that case”, said
Arduino, “allow me to introduce Uno, the One.” He tossed the remnants of the biscotti to Rick and picked
up a small blue printed circuit board containing a few ICs, a bunch of headers with numbered pins and
what looked like USB and power connectors.

“Pretty spiffy”, she said. “What is it?” Arduino’s eyes lit up. “It’s an open source microcontroller
development board, and when I say ‘open source’ I mean both software and hardware. The software
distribution includes extensive examples, complete library source code, and all the data you could want
on the AVR.” “What’s an AVR?” came the dame’s reply. “AVR is a line of microcontrollers from Atmel.
The Uno uses an ATmega 328P with 32k of on-chip programmable flash memory, 2k of SRAM data
memory and 1k of EEPROM. 32 general purpose registers. Pipelined Reduced Instruction Set Computer
with Harvard architecture. Most instructions require only one tick of the 16 MHz clock.” Arduino’s
concentration was broken by a hissing sound coming from behind a large stack of books. “Ahhh! Can I
interest either of you in a cup of espresso?” he asked. “Never after lunch”, said Rick. He knew Arduino’s
hyper-caffeinated concoction would have him bouncing off the walls all afternoon. “And you, Miss
Seesi?” Arduino queried. “M

Sipping the steaming beverage, she looked over the board intently. “The labeled port pins on the headers
are convenient- seems pretty small though. Are you sure it can handle the job?” she asked. “No problem!”
said Arduino. He pulled out a couple of slightly crumpled and dog-eared pieces of paper from under a
stack of CD-ROMs and placed them on the desk. First was a block diagram of the 328P as used on the
Uno, the second a more detailed schematic of the board:

“You’ve got access to three IO ports”, he began, “B, C and D. Digital IO with programmable pull-down
resistor. All IO is memory mapped so you can read from and write to external devices as if they were just
ordinary variables using the C programming language. A Universal Synchronous-Asynchronous
Receiver-Transmitter, or USART, already programmed to communicate with a host computer via USB.”
She interrupted him. “So I can send text back and forth between the two? That would make debugging
pretty easy.” “You bet!” said Arduino, obviously getting excited. “Not only that, but you’ve got six 10 bit
analog to digital converter channels and three timer-counters; two eight bit and one 16 bit. Plus, six
outputs can generate pulse width modulation signals.” “What about interrupts?” she asked. “I’ll need
interrupts.” “Multiple levels,” said Arduino, “internal and external. There’s a reset button already on the
board.”

“What about power?” she asked. “Multiple options”, said Arduino. “You can power it from the USB
cable. You know, USB will supply up to 100 mA to an un-enumerated device and up to 500 mA to an
enumerated device. If that’s not enough, you can also plug in an external supply, the wall-wart kind, or
even hook in a regulated five volt source so you can supply power to relays, motors, whatever. You’d
power the big wire items off-board, of course. No need to run those currents through the board traces.
Whatever you choose, though, the Uno will intelligently figure out where to get its power from.”
The dame was getting more interested and needed further detail. “Great, but what will the chip deliver,
you know, fan out or drive.” “Generally speaking,” Arduino began, “the IO pins can sink or source up to
40 mA each. The entire microcontroller should be limited to 200 mA total draw to stay within thermal
limits so you obviously can’t drive a whole bunch of pins to maximum current capability at the same
time. No big deal, that’s why they make drive circuits, right?” Rick and the dame both nodded knowingly.
The office was silent as the three of them peered at the little board. The dame looked up. “What about the
programming interface? Command line or IDE?” Arduino waved his hand and responded, “The IDE runs
under Windows, Mac OS and Linux. You can bypass that if you want and go command line, but…”
“Fine, fine”, she interrupted, “and this library, it’s a straight jacket, right?” “No, no!” insisted Arduino.
“It’s a nice library and you can use as much or as little of it as you want. Even insert assembly op codes.”
Assembly op codes. The thought sent a shiver down Rick’s spine. He had spent a month one day trying to
debug a device driver written in 8086 assembly. Never again.

It seemed that Arduino was holding something back. “Sounds good but you’re not giving me the whole
story are you?” she asked him. “What’s the catch?” “No catch,” replied Arduino, “but there’s one thing.
One small thing that sometimes bites the beginners.” The dame raised her eyebrows and demanded,
“And?”
“Like most controllers,” Arduino began, “the AVR uses a memory mapped IO address for writing to a
port. For example, you might write to PORTB to light an LED.” “So?” the dame responded, “That’s not
odd.” “Very true,” said Arduino, “but when it comes to reading from those same physical pins, they use a
different address, in this case PINB, instead of reusing PORTB.”
“Wait,” stammered the dame, “it’s the same physical pin and if I write to it, I use PORTB but if I read
from it I use PINB?”

“Don’t confuse pins and ports”, said Arduino as a look of melancholy crept across his face. “You must
remember this, a port is just a port, a pin is just a pin. The fundamental things apply, as the clock ticks
by.” The dame was shaken. “But I…” she started. “Look, you gotta get the IO straight, understand?” said
Arduino. His expression grew serious and he looked at her squarely. “You gotta get it plain or you’ll
regret it. Maybe not today, maybe not tomorrow, but soon and for the rest of your life!” Her hand brushed
lightly across the Uno as she turned, and wiping a tear from her eye, she headed out the office door. Rick


watched as she walked briskly down the hall. Some distance past the lab her silhouette disappeared into a
fog that had mysteriously formed out of nowhere accompanied by the dull roar of a DC3’s idling engines.
“She’s got the Uno”, said Rick. Arduino nodded, “Yes, I know. I’ve got plenty more where that one came
from. All I need is a good lab tech to help me build more prototypes for Project Falcon using them. You
interested?” A wry smile grew on Rick’s face. “This Falcon, is it Maltese?” “Why yes, yes it is” came the
response. “Arduino,” Rick said, “I think this is the beginning of a beautiful friendship.”11
 
