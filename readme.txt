Click "Download ZIP" to download everything.  Installers are included for Windows and Mac.

--Important Note for MAC USERS--
If you get an error "proftweak.app is damaged and can't be opened" - it is due to your Gatekeeper settings requiring apps be signed.  See http://support.apple.com/kb/HT5290 for the solution.
To fix run:
    codesign -s - -v --force proftweak.app/
(In case you dont have the codesign binary - download Xcode from the App store)

The general info / docs on ProfTweak are at:
http://nothinglabs.blogspot.com/2013/09/introducing-proftweak-makerware-profile.html

If something isn't working for you - there's a decent chance it's addressed there.  If things still don't work for you - feel free to bug me.

ProfTweak is built with Processing 2.0.3 and G4P v3.3 - use those versions only!  Building Proftweak with newer versions of Processing causes an issue launching from Makerware / Makerbot Desktop.  Newer versions of G4P have an issue where a leading “ “ can get appended to text entries.

ProfTweak is licensed as http://creativecommons.org/licenses/by-sa/3.0/

-Rich Olson
www.nothinglabs.com
rich@nothinglabs.com

