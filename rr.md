pinterest for protest IMAGES TO IMAGE PROCESS: https://www.pinterest.com/yellowbuttersunshine/images/
slideshow is better though - https://docs.google.com/presentation/d/1jHaVKnvHPHxpCceC9elZXl2W6Hat8ElN3-1e516ZwGU/edit?usp=sharing
# BASE HYDRATEXT 

await loadScript("https://hyper-hydra.glitch.me/hydra-text.js")

hydraText.font = "serif"
hydraText.lineWidth = "2%"
str = " hydra_! "
solid(1,.2)
	.blend(src(o0).scale(1.02).colorama(.02)) //take out 
	.layer(text(str)) // take out
	.diff(strokeText(str).modulateScale(noise(1,1), .4)) // take out 
	.out()


 # code sample can mess around with speed, colors, and even shape 
// licensed with CC BY-NC-SA 4.0 https://creativecommons.org/licenses/by-nc-sa/4.0/
//port
//by Marianne Teixido
//https://marianneteixido.github.io/
speed = 0.1
osc(5, 0.9, 0.001)
    .kaleid([3,4,5,7,8,9,10].fast(0.1))


# image tings 
s0.initScreen()
src(s0).colorama(0.1).modulateScale(osc(10,0.1)).out()

    .color(0.1,0.7,0)
    .colorama(0.4)
    .rotate(0.009,()=>Math.sin(time)* -0.001 )
    .modulateRotate(o0,()=>Math.sin(time) * 0.003)
    .modulate(o0, 0.9)
    .scale(0.9)
    .out(o0)
