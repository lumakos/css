# css

<b>Using REM in LESS</b><br/>

@defaultBrowserFontSize: 13;<br/><br/>

// These are the root font sizes.<br/>
// These help us calculate font sizes in rems<br/>
@rootFontSize: (@defaultBrowserFontSize / 16) * 1rem;<br/><br/>

// Paddings & margins<br/>
@spacing: (@rootFontSize * 10) / @defaultBrowserFontSize;<br/>
@spacing-xs: @spacing*0.5;<br/>
@spacing-sm: @spacing;<br/>
@spacing-md: @spacing-xs*3;<br/>
@spacing-lg: @spacing-xs*4;<br/>
@spacing-xl: @spacing-xs*6;<br/><br/>

<b>Using variables in LESS</b><br/>
@userProtectionImage: '/img/shield-large.png';<br/>

