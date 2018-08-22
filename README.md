# css

<b>Using REM in LESS</b>

@defaultBrowserFontSize: 13;

// These are the root font sizes.
// These help us calculate font sizes in rems
@rootFontSize: (@defaultBrowserFontSize / 16) * 1rem;

// Paddings & margins
@spacing: (@rootFontSize * 10) / @defaultBrowserFontSize;
@spacing-xs: @spacing*0.5;
@spacing-sm: @spacing;
@spacing-md: @spacing-xs*3;
@spacing-lg: @spacing-xs*4;
@spacing-xl: @spacing-xs*6;

<b>Using variables in LESS</b>
@userProtectionImage: '/img/shield-large.png';

