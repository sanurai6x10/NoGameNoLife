:root {
	--transparencycolor:			0,0,0;						/* default:	0,0,0																								*/
	--transparencyalpha:			0.25;						/* default: 0.15				(general darkness of the app)													*/
	--messagetransparency:			0.25;						/* default: 0.5					(additional shadows behind messages, set to 0 to remove boxes)					*/
	--guildchanneltransparency:		0.25;						/* default: 0.05				(additional darkness for guild/channel list)									*/
	--memberlisttransparency:		0.5;						/* default: 0.0					(additional darkness for member list)											*/
	--accentcolor:					190,78,180;					/* default: 190,78,180			(RGB-format - blurple: 114,137,218 bd-blue: 58,113,193)							*/
	
	--font:							Whitney, Helvetica Neue, Helvetica, Arial, sans-serif;		/* font used in most places														*/
	--textshadow:					transparent;				/* default: transparent			(textshadow for text ontop of accentcolor nodes, ONLY accepts a color, no px)	*/
	--settingsicons:				1;							/* Use Settings Icons in User/Server/Channel Settings: 1 = yes, 0 = no											*/
	
	--background:					url(https://cdn.hipwallpaper.com/i/66/35/3ZfhXi.jpg);	/* general background image				*/
	--backgroundposition:			center;						/* default: center				(position of background - values: [center/top/right/bottom/left])				*/
	--backgroundsize:				cover;						/* default: cover				(sizefit of background - values: [cover/contain/auto])							*/
	--backgroundblur:				unset;						/* default: unset				(blur in px, only works when --background is set to an image)					*/
	
	--popout:						var(--background);			/* default: var(--background)	(change to use another background/color for modals/popouts)						*/
	--popoutposition:				var(--backgroundposition);	/* default: center				(position of popout - values: [center/top/right/bottom/left])					*/
	--popoutsize:					var(--backgroundsize);		/* default: cover				(sizefit of popout - values: [cover/contain/auto])								*/
	--popoutblur:					var(--backgroundblur);		/* default: unset				(blur in px, only works when --popout is set to an image)						*/
	
	--backdrop:						rgba(0,0,0,0.85);			/* default: rgba(0,0,0,0.85)	(change to use another background/color for backdrops)							*/
	--backdropposition:				var(--backgroundposition);	/* default: center				(position of backdrop - values: [center/top/right/bottom/left])					*/
	--backdropsize:					var(--backgroundsize);		/* default: cover				(sizefit of backdrop - values: [cover/contain/auto])							*/
	--backdropblur:					var(--backgroundblur);		/* default: unset				(blur in px, only works when --backdrop is set to an image)						*/
	
	--version1_0_5:					none;						/* DO NOT CHANGE THIS VARIABLE , USED TO HIDE UPDATE NOTICE														*/
}
