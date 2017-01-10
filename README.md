# cssAnimations
all my fav css animations

#Infinate scroll across screen (clouds drifting)
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
