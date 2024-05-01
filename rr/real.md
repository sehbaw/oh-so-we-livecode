# expose
await loadScript("https://hyper-hydra.glitch.me/hydra-text.js")

hydraText.font = "serif"
hydraText.lineWidth = "50%"
str = "the ischool: 'we are so diverse! we aim for social good!'\n\n\n also, the ischool: threatens students for speaking out against a genocide,\n\n employs zionists (IDO SIVAN-SEVILLA) and racists (TOO MANY TO NAME HERE),\n\n\n\n and full of ignorant weirdos"
//https://ischool.umd.edu/wp-content/themes/ischool/images/iSchool-Logo-White-w-Tagline.png - link to the page as it does not work with initImaGE I AM SO GLAD 
s0.initImage("https://ischool.umd.edu/wp-content/themes/ischool/images/iSchool-Logo-White-w-Tagline.png")
src(s0).scale(0.3)
.color(0.9,0.7,0.1)
	.layer(text(str))
	.diff(strokeText(str).modulateScale(noise(1,1), .4))
	.out()
