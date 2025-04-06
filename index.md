# Benjamin Miller
Hi! I am Benjamin Miller, a second year computer science student at **UC San Diego**!


### My Favorite Qoute
A Qoute that Speaks to me:
> Computer science is no more about computers than astronomy is about telescopes. - Edsger Dijkstra

### Recent Project
I recently wrote code that controls the mouth of an audio animatronic. A part of the code I am specifically proud of is:
```
while (1) {
    	if ((err = snd_pcm_readi(capture_handle, buffer, FRAMES)) < 0) {
        	fprintf(stderr, "\nRead error: %s\n", snd_strerror(err));
        	snd_pcm_prepare(capture_handle);
    	}
    	move_servo_based_on_amplitude(buffer, FRAMES);
}
```
[Link to the full repository](https://github.com/BenMiller0/teaAnimatronic/tree/main)

[Here](ConceptArt.jpg) 


Important Section links
[My Recent Project](#Recent-Project).
[Top section](#Benjamin-Miller).
