SampleChest v1.1
===========

SampleChest v1.1 is critical artware [softwaer+art] + a creative piracy tool for creating video sample libraries by ripping videos from today’s richest AV cultural repository, YouTube. SampleChest v1.1 is distributed under the copy&lt;it&gt;right license, copying/sharing is encouraged/appreciated. 
* * * * 

<code>\n
    /***************************************\
    *                                      *
    *         SAMPLE CHEST v1.1            *
    *     (ɔ) 2010-12 by Nick Briz         *  
    *        http://nickbriz.com           *
    *    http://piraticalpractices.net     *
    *                                      *
    \***************************************/
</code>

#### "[...] it’s okay to copy! Believe in the process of copying as much as you can; with all your heart is a good place to start – get into it as straight and honestly as possible. Copying is as good (I think better from this vector-view) as any other way of getting ‚’there.’ [...]" —Phil Morton [COPY&lt;IT&gt;RIGHT]


* * * * 

### [TERMS + AGREEMENT + PHILOSOPHIES] ####


0. i hereby agree that [conventional] notions of originality are myths + that the cultural products i produce [both in content && concept] are [re]combinations of [pre]existing ideas + that any feelings i may have to the contrary are simply cases of cryptomnesia + that i recognize any future work i produce to be undiscovered public knowledge.

1. i understand [historically] that the laws of what we now call intellectual property have been developed by institutions of power who have sought to maintain control over information && culture to further their own agendas + that the invention && development of these laws have had little to do with what we [traditionally] call authorship

2. economically, i understand my ideas [+any digital manifestation they may take] to be a non-rivalrous good—that is to say, that additional units can be infinitely copied/shared at no cost && that any [re]use can not prevent any prior/existing use—and as such should be shared freely for the moral and mutual instruction of wo/man + that any restrictions on [re]use would impose inefficient && unnatural scarcity. 

3. piracy is a refusal to comply with the established forced scarcity agenda. piracy is a compositional prerogative. piracy is-not plagiarism nor is it imposterism + attribution is key to this distinction—not in the interest of maintaining [conventional] notions of authorship—in the interest of deep linkage && participatory culture[s]. 

4. i hereby forfeit any intellectual property—imposed on me by any copyright regimes—on any cultural products I may render from the use of this artware + if i choose to share my cultural products i will do so without any restrictions on its [re]use. 

* * * * 


### //NOTES FOR BUILDING FROM SOURCE: ###
SampleChest was composed using Max/MSP + [this command line project](https://github.com/rg3/youtube-dl/) + [this shell object](http://www.maxobjects.com/?v=objects&id_objet=1194&requested=shell&operateur=&id_plateforme=&id_format=&PHPSESSID=f5e6adb64b07dbe30d12166e02b3dbcb). In addition to forking/modding/etc, the source can be easily appropriated into other Max/MSP projects. There is a little set-up you need to do before this patch will run properly

0. copy the [shell.mxo](http://www.maxobjects.com/?v=objects&id_objet=1194&requested=shell&operateur=&id_plateforme=&id_format=&PHPSESSID=f5e6adb64b07dbe30d12166e02b3dbcb) and shell.help to wherever you keep your max objects

1. build the patch into an application 
    * copy everything in SampleChest.txt && in Max choose FILE > NEW FROM CLIPBOARD && save as "SampleChest"
    * open [p menuStuff] (sub pather) and connect [loadmess 1] to [menubar 5]
    * FILE > BUILD COLLECTIVE/APPLICATION && include file "icon.incs" (change 'include' to 'appicon' in build window)
    * Buile (as Application)
    
2. right click the app and click "Show Package Contents"

3. create a folder called "video" inside the "contents" folder

4. copy the [youtube-dl.sh](http://rg3.github.com/youtube-dl/) script into the "video" folder

5. then navigate into the 'support' directory, then into the 'interfaces' dirctory, and replace the maxinterface.json file with the one from this repo

[NOTE] at this point the app and the patch should run fine from the desktop and other folders, however if the app is too far away from the root dir it will not work. If there is over 50 characters in the path between the root dir and the app, it will NOT work. 


### //THANKS: ###
* to [Mark Beasley](http://mark-beasley.com/) for help w/ the python script
* to [youtube-dl](http://rg3.github.com/youtube-dl/)
* to [phihag](https://github.com/rg3/youtube-dl/issues/135) for the fork to workaround Youtube's URL map key switch-a-ro 
* to Bill Orcutt for a super rad [unix shell](http://www.maxobjects.com/?v=objects&id_objet=1194&requested=shell&operateur=&id_plateforme=&id_format=&PHPSESSID=f5e6adb64b07dbe30d12166e02b3dbcb) object for max
* to all the artists/writers who's ideas I've plundered throughout this artware, [Phil Morton](http://www.copyitright.org/), [jonCates](http://systemsapproach.net/), [John Oswald](http://www.plunderphonics.com/), [Elisa Kreisinger](http://popculturepirate.com/), [Netochka Nezvanova](http://en.wikipedia.org/wiki/Netochka_Nezvanova), [Jonathan Lethem](http://www.jonathanlethem.com/), [Adrian Johns](http://www.adrianjohns.com/), [Rick Falkvinge](http://falkvinge.net/), and [Yochai Benkler](http://benkler.org/).