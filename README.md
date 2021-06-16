# Sheet music generator

# What is it?

Are you an adult who just started learning classical music? Do you find it hard to read sheet music? Do you find it even harder to read sheet music, while at the same time trying to figure out where to move your hands and fingers to play the right notes? If so, this is for you.

Simply open the **index.html** file in your browser and it will generate a page of random sheet music. Take a print-out of this page and practise with it. It will improve your sight reading skills significantly over time. This is because, random notes (unlike musical passages) force your eyes to pick up every note, since there is no discernible pattern to them.

Children, in particular, can hugely improve their sight reading abilities using this tool.

# Technicals

I wrote this tool for someone who was just starting to learn classical music and was struggling with reading sheet music. This was written around 2015 or so, around the time that ES6 just came out, so it lacks many of the bells and whistles of "modern" JS (I did change some of the *var* keywords to *let* though). You are free to modernize the code to your heart's content. The Javascript code appears inline within the **index.html** file itself. I didn't bother pulling the JS into its own separate file, as it is not too much of code.

# Improvements

You can get creative and add any number of ideas to this tool. For exacmple, you could provide options to generate random notes obeying a specific key signature or time signature. You can even specify the range of notes, which is a way to specify the "difficulty level". Using these (and many more) ideas, you can generate an entire *book* of random sheet music, with progressively increasing difficulty.
