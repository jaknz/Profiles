## Block Sierra Installer
Prevents end users from launching the macOS Sierra installer from the Applications folder. Note that enterprising users can move the app out of the Applications folder and run it, as it is blacklisting the full path.

## Chrome Blacklist
Blocks the following Chrome VPN and malware extensions:

Identifier | Name
--- | ---
ckiahbcmlmkpfiijecbpflfahoimklke | Gom VPN
mjnbclmflcpookeapghfhapeffmpodij | Ultrasurf
gkojfkhlekighikafcpjkiklfbnlmeio | Unlimited Free VPN - Hola
fdcgdnkidjaadafnichfpabhfomcebme | ZenMate VPN
kpiecbcckbofpmkkkdibbllpinceiihk | DotVPN
nlbejmccbhkncgokjcmghpfloaajcffj | Hotspot Shield Free VPN Proxy
omghfjlpggmjjaagoclmmobgdodcjboh | Browsec VPN
bibmocmlcdhadgblaekimealfcnafgfn | FreeMyBrowser VPN
omdakjcmkglenbhjadbccaookpfjihpa | TunnelBear
ceopoaldcnmhechacafgagdkklcogkgd | OnlineMapFinder
fahgbckbihhfifpchidpdaapinhkjfnc | Phases of the Moon
hbdnlaaihddmiaeapkodgenhbofpmmlf | Loadtime Meter

## Chrome Whitelist
Allows forcible installation of extensions. Installs "Office Editing for Drive" as an example.
Blocks ALL extensions except the following trusted Google extensions:

Identifier | Name
--- | ---
gecgipfabdickgidpmbicneamekgbaej | Chrome Web Store Launcher
aohghmighlieiainnegkcijnfilokake | Google Docs
ghbmnnjooekpmoecnnnilnnbdlolhkhi | Google Docs Offline
felcaaldnbdncclmgdcncolpebgiejap | Google Sheets
aapocclcgogkmnckokdopfmhonfmgoek | Google Slides
gbkeegbaiigmenfmjfclcdgdpimamgkj | Office Editing for Drive

## Munkireport Config
Forces MunkiRerport settings instead of having to change them by doing fake incremental Munkireport packages. Change URL and flags as needed.