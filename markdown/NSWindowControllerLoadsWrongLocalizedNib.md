

I have been developping an app in English and just started localizing it in French.
My General/MainMenu.nib loads the French version correctly (I have set my International perferences to do so), but any new window created thru :

    General/[NSBundle loadNibNamed:@"General/NewManualGroupSheet" owner:windowController];


does not load the French version, but the English one.
I have looked all over but didn't find anything...