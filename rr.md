pinterest for protest IMAGES TO IMAGE PROCESS: https://www.pinterest.com/yellowbuttersunshine/images/
slideshow is better though - https://docs.google.com/presentation/d/1jHaVKnvHPHxpCceC9elZXl2W6Hat8ElN3-1e516ZwGU/edit?usp=sharing

# ACTUAL BASE 


await loadScript("https://hyper-hydra.glitch.me/hydra-text.js")
str = " hydra_! "
hydraText.font = "serif"
hydraText.canvasResize = 3;
hydraText.lineWidth = "1%"
hydraT
s0.initScreen()

src(s0).colorama(0.2)
.layer(text(str))
	.diff(strokeText(str).modulateScale(osc(1,1), .4))
.out(o0)










# BASE HYDRATEXT (without cganging visuals) 

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
#layer text on top of visuals other than hydatext base 


await loadScript("https://hyper-hydra.glitch.me/hydra-text.js")
str = " hydra_! "
hydraText.font = "serif"
hydraText.canvasResize = 3;
hydraText.lineWidth = "1%"
hydraT
s0.initScreen()

src(s0).colorama(0.2)
.layer(text(str))
	.diff(strokeText(str).modulateScale(osc(1,1), .4))
.out(o0)

#visuals 


# ACTUAL CODE WE USED 

await loadScript("https://hyper-hydra.glitch.me/hydra-text.js");

//str = "MY UNIVERSITY IS\nFUNDING A GENOCIDE\nAND ALL I GOT WAS\nTHIS LOUSY PROJECTOR";
str = "NO TECH FOR APARTHEID"

window.hydraText.font = "serif";
window.hydraText.canvasResize = 3;
window.hydraText.lineWidth = "1%";
//s0.initImage("https://cdn.discordapp.com/attachments/1186720117128704162/1234649744895381535/image.png?ex=663180ad&is=66302f2d&hm=17234016af189e46b5a5ef1a7c09c1a285875748b3f3184748a6b8f025ad3f3d&") //if we wanna do image stuff 
//src(s0).saturate(.modulateScale(osc(10,0.1,0.1),0.1)


speed = 0.08

osc(5, 0.9, 0.001)
    .kaleid([3,4,5,7,8,9,10].fast(0.1))
    .color( 0.3,0.3,1)
   // .colorama(0.6)
    .rotate(0.009,()=>Math.sin(time)* -0.001 )
    .modulateRotate(o0,()=>Math.sin(time) * 0.003)
    .modulate(o0, 0.9)
    .scale(0.9)





  
//.layer(text(str))
	//.diff(strokeText(str).modulateScale(osc(1,1), .01))
//.out(o0) 
.layer(text(str).modulateScrollY(osc(3, 2), 0.5, 0))
	.mult(strokeText(str).modulateScale(osc(1,1), .4).invert())
.out(o0) 

-- another piece of code-- 


await loadScript("https://hyper-hydra.glitch.me/hydra-text.js");

//str = "MY UNIVERSITY IS\nFUNDING A GENOCIDE\nAND ALL I GOT WAS\nTHIS LOUSY PROJECTOR";
str = "NO TECH\nFOR APARTHEID"
str2 = "DISCLOSE\nDIVEST"
window.hydraText.font = "serif";
window.hydraText.canvasResize = 3;
window.hydraText.lineWidth = "3%";
//s0.initImage("https://cdn.discordapp.com/attachments/1186720117128704162/1234649744895381535/image.png?ex=663180ad&is=66302f2d&hm=17234016af189e46b5a5ef1a7c09c1a285875748b3f3184748a6b8f025ad3f3d&") //if we wanna do image stuff 
//src(s0).saturate(.modulateScale(osc(10,0.1,0.1),0.1)


speed = 0.08

osc(0.5,1.25).mult(shape(1,0.09).rotate(1.5))
  .diff(gradient())
  .add(shape(2,2).blend(gradient(1)))
  .modulate(noise()
            .modulate(noise().scrollY(1,0.0625)))
  .blend(o0)
  .color(1,-0.5,-0.75)
  .color(-0.5,1,-0.75)
  



  
//.layer(text(str))
	//.diff(strokeText(str).modulateScale(osc(1,1), .01))
//.out(o0) 
.layer(text(str).modulateScrollY(osc(3, 2), 0.5, 0))
	.mult(strokeText(str2).modulateScrollX(voronoi(1, 5), .4).invert().repeatX(2).repeatY(2))
.out(o0) 



FOR NEXT TIME - 
// licensed with CC BY-NC-SA 4.0 https://creativecommons.org/licenses/by-nc-sa/4.0/
// "the-wall"
// Alexandre Rangel
// www.alexandrerangel.art.br/hydra.html

speed=.0222
osc(48,-.1,0).thresh([.3,.7].fast(.75),0).color(0,0,1)

.add(
    osc(28,.1,0).thresh([.3,.7].fast(.75),0).rotate(3.14/4)
    .color(1,0,0)
    .modulateScale( osc(64,-.01,0).thresh([.3,.7].fast(.75),0) )
)
.diff(
    osc(28,.1,0).thresh([.3,.7].fast(.5),0).rotate(3.14/2)
    .color(1,0,1)
    .modulateScale( osc(64,-.015,0).thresh([.3,.7].fast(.5),0) )
)
.modulateRotate( osc(54,-.005,0).thresh([.3,.7].fast(.25),0) )
.modulateScale( osc(44,-.020,0).thresh([.3,.7].fast(.25),0) )
.colorama( ()=>Math.sin(time/27)*.01222+9.89)
.scale(2.122)

.out()

-- MORE CODE --- 
await loadScript("https://hyper-hydra.glitch.me/hydra-text.js");

//str = "MY UNIVERSITY IS\nFUNDING A GENOCIDE\nAND ALL I GOT WAS\nTHIS LOUSY PROJECTOR";
str = "UMD\nYOU\nCAN'T\nHIDE"
str2 = "YOU'RE\nINVESTING\nIN GENOCIDE"
window.hydraText.font = "serif";
window.hydraText.canvasResize = 3;
window.hydraText.lineWidth = "1%";
//s0.initImage("https://cdn.discordapp.com/attachments/1186720117128704162/1234649744895381535/image.png?ex=663180ad&is=66302f2d&hm=17234016af189e46b5a5ef1a7c09c1a285875748b3f3184748a6b8f025ad3f3d&") //if we wanna do image stuff 
//src(s0).saturate(.modulateScale(osc(10,0.1,0.1),0.1)


speed=.0222
osc(48,-.1,0).thresh([.3,.7].fast(.75),0).color(0.9,0,0.2 )

.add(
    osc(28,.1,0).thresh([.3,.7].fast(.75),0).rotate(3.14/4)
    .color(0.9,0,0.2 )
    .modulateScale( osc(64,-.01,0).thresh([.3,.7].fast(.75),0) )
)
.mult(
    osc(28,.1,0).thresh([.3,.7].fast(.5),0).rotate(3.14/2)
    .color(0.9,0,0.2)
    .modulateScale( osc(64,-.015,0).thresh([.3,.7].fast(.5),0) )
)
.modulateRotate( osc(54,-.005,0).thresh([.3,.7].fast(.25),0) )
.modulateScale( osc(44,-.020,0).thresh([.3,.7].fast(.25),0) )
//.colorama( ()=>Math.sin(time/27)*.01222+9.89)
.scale(2.122)

  
//.layer(text(str))
	//.diff(strokeText(str).modulateScale(osc(1,1), .01))
//.out(o0) 
.diff(text(str).modulateScrollX(osc(3, 2), 0.5, 0))
	.diff(strokeText(str2).modulateScrollX(osc(1, 5), .4).color(1,1,1).scale(0.9).repeatX(3).repeatY(3))
.out(o0) 












































































































































































































