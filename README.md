# cssAnimations
all my fav css animations

##Infinate scroll across screen (clouds drifting)
.fcloud02 {
		top:200px;
		z-index: 200;
		opacity: .5;
    /* name, duration, delay, ease function, repeat num, use from keyframe to start it off */
		animation: drift 4s 1s linear infinite backwards;
	}

@keyframes drift {
	from{transform: translateX(-50vw);}
	to {transform: translateX(100vw);}
}

## sprites with 'step'
.sprite {
	width:500px;
	height:500px;
	display:block;
	background:transparent url(walker_frames.png) 0 0 no-repeat;
	margin:3em auto;
	animation: walker 1s steps(10) infinite;
}


@keyframes walker {
	0% {background-position: 0 0;}
	100% {background-position: 0 -5000px;}
}
