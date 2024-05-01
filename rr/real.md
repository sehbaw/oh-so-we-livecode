# expose
await loadScript("https://hyper-hydra.glitch.me/hydra-text.js")

hydraText.font = "serif"
hydraText.lineWidth = "50%"
str = "the ischool: 'we are so diverse! we aim for social good!'\n\n\n also, the ischool: threatens students for speaking out against a genocide,\n\n employs zionists and racists,\n\n\n\n and full of ignorant weirdos"
s0.initScreen()
src(s0).scale(0.3)
.color(0.9,0.7,0.1)
	.layer(text(str))
	.diff(strokeText(str).modulateScale(noise(1,1), .4))
	.out()
