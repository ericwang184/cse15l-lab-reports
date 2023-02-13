# Lab 3
## grep -r command line option
This is the first example of the grep -r command
```
[cs15lwi23aqw@ieng6-201]:skill-demo1-data:420$ grep -r "Lucayans" written_2
written_2/travel_guides/berlitz2/Bahamas-History.txt:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
written_2/travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
```
For the example up top, grep -r will search recursively all the files under each directory recursively. So it will search every file in written_2, then in the written_2/travel_guides folder, then written_2/travel_guides/berlitz2 folder, then written_2/travel_guides/berlitz2/Bahamas-History folder, and then listing out the files that have "Lucayans". 
This is the second example of the grep -r command
```
[cs15lwi23aqw@ieng6-201]:skill-demo1-data:436$ grep -r Israel
Binary file .git/index matches
written_2/non-fiction/OUP/Berk/ch2.txt:Collectivist values also alter the way teachers and children think about classroom learning. Were you to visit a school on an Israeli kibbutz (cooperative agricultural settlement), you would ﬁnd an explicit emphasis on cooperation and avoidance of pupil comparisons, and a far more positive attitude toward children who seek help than is common in American schools. When asked why children look at each others’ work, kibbutz pupils mention the importance of connecting with others to acquire new skills. They explain, “If your picture looks crooked, you would want to see your friend’s paper to learn how to make it straight,” or “If you aren’t sure what you’re supposed to do, then you should check.” To the same question, American and Israeli urban children typically respond, “I would want to see whose picture was the best,” or “I might be wondering whether she got more right than I did.”5 
written_2/non-fiction/OUP/Fletcher/ch1.txt:The place of “blood” in the religious tradition of redemption proves to be subtle and problematic. There are some strains in the Jewish tradition that link the letting of blood with returning the soul to God. The “redeemer of blood” reminds us of that connection, as does the popular view that the founding of Israel stood in some kind of organic relationship with the Holocaust. The connection between blood and salvation becomes much stronger, however, in the Christian interpretation of its Jewish legacy. The theme of blood spilling from the body becomes powerful in the crucifixion and reaches its apotheosis in the faith that a great battle, an Apocalypse, must precede the Second Coming of the Messiah. The spilling of blood in a great battle is understood instinctively as the suffering that must precede redemption. As John Brown was led to the gallows on the eve of the Civil War, having unsuccessfully sought to stimulate a slave revolt, he handed one of his guards a note, “I John Brown am now quite certain that the crimes of this guilty land will never be purged away but with blood.”2
written_2/non-fiction/OUP/Fletcher/ch6.txt:The ancient Israelites would spend forty years wandering in the desert before the passing of time would generate a new people, unaffected by the mentality of the “fleshpots of Egypt.” Modern political conditions rarely offer this luxury. The Soviets dreamed of creating a “new man” who would regard the communist system as the natural backdrop for cooperation. History never gave them the chance. But Germans could engineer a radical transformation after the fall of the Berlin Wall and the unification of the country. The West Germans absorbed the former German Democratic Republic and then restaffed the courts and the law faculties with new personnel, drawn overwhelmingly from Western ranks.
written_2/non-fiction/OUP/Fletcher/ch9.txt:The same could be said of devotion to the nation. The state must engage in some elementary gestures of national pride. It must define and disseminate a flag, a national anthem, and celebrate holidays such as the Fourth of July, Veterans’ Day, and the birthdays of great national leaders. Nations that fail to do these things have trouble melding their people into a single culture of national identity. A good example is Israel, which has yet to find a holiday that Jews and Arabs can celebrate together. We live in a time of national disintegration—witness Czechoslovakia, the Soviet Union, and the near-misses in Canada—and, therefore, the state is properly advised to cultivate a common identity and a sense of shared history and destiny.
written_2/non-fiction/OUP/Fletcher/ch9.txt:There is no doubt that free speech has its victims, and in most European societies and in Canada, the courts rush in to protect the victims against being offended. A good example is the way every major jurisdiction outside the United States treats Holocaust denial. Someone publishes a book saying that Auschwitz never happened, that it is a lie propagated by the Jews. This is a punishable act in Germany, France, Israel, the Netherlands, Canada—just about everywhere where people believe that the government must intervene in order to protect those who might be disturbed and offended by the obscene lie. By intervening and putting the Holocaust denier on trial, of course, they only broadcast the lie to a larger audience, and they convert the mad dissident into a martyr in his own circle.
written_2/non-fiction/OUP/Rybczynski/ch3.txt:I mentioned the New York Public Library competition when I gave a public lecture in connection with a recent architectural competition for the new Salt Lake City Public Library. The library board had conducted a national search for an architect, visited new libraries across the country, and solicited proposals from prominent architects. They had narrowed their list to four firms: Charles Gwathmey and Robert Siegel are respected New York architects with a long record of university buildings and museums, including a new library of science, industry, and business for the New York Public Library system. Moshe Safdie had built major civic buildings in Israel, Canada, and the United States, and recently completed the public library in Vancouver, British Columbia. Moore Ruble Yudell is a Los Angeles firm founded by the late Charles Moore, with whom John Ruble and Buzz Yudell built several university libraries and a public library in Berlin. Will Bruder, the least well-known of the four, is a southwesterner and the architect of the new, well-regarded Phoenix Public Library.
written_2/travel_guides/berlitz1/HandRIsrael.txt:        9122. By the beach, in its own lovely grounds, next to Israel’s only
written_2/travel_guides/berlitz1/HandRIsrael.txt:        (02) 620 8888, fax (02) 620 8880. Israel’s best accommodation option,
written_2/travel_guides/berlitz1/HandRIsrael.txt:        being one of Israel’s best kibbutz accommodations, situated right on
written_2/travel_guides/berlitz1/HandRIsrael.txt:        (04) 830 6211. The Israeli and Continental cooking is reasonable, but
written_2/travel_guides/berlitz1/HandRIsrael.txt:        Street; Tel. (09) 580 402. Many Israelis swear that these are the best
written_2/travel_guides/berlitz1/HandRIsrael.txt:        Windmill; Tel. (02) 625 1042. Israel’s finest French restaurant,
written_2/travel_guides/berlitz1/HandRIsrael.txt:        portions of Israeli meat are served here, with lamb and veal dishes
written_2/travel_guides/berlitz1/HandRIsrael.txt:        excellent, innovative Israeli and international nouvelle cuisine.
written_2/travel_guides/berlitz1/HandRJerusalem.txt:        Israel or through airlines as part of land-package arrangements. The
written_2/travel_guides/berlitz1/HandRJerusalem.txt:        substantial “Israeli” breakfast; in East Jerusalem, the price usually
written_2/travel_guides/berlitz1/HandRJerusalem.txt:        Hotel rates in Israel are always quoted in US dollars. The
written_2/travel_guides/berlitz1/HistoryEgypt.txt:        for Israel.
written_2/travel_guides/berlitz1/HistoryEgypt.txt:        Jewish state of Israel founded on land so recently Islamic Palestine
written_2/travel_guides/berlitz1/HistoryEgypt.txt:        embroiled in several unsuccessful short wars with Israel that severely
written_2/travel_guides/berlitz1/HistoryEgypt.txt:        weakened the country and left the Sinai region in Israeli hands.
written_2/travel_guides/berlitz1/HistoryEgypt.txt:        recognize the state of Israel — other Arab states were aghast and
written_2/travel_guides/berlitz1/HistoryEgypt.txt:        as a moderator and offering Cairo as a venue for Arab/Israeli peace
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        The land we know today as Israel has had many names during
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        of the Philistines), then Israel and Judea, before reverting to
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        the modern State of Israel was proclaimed.
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        best source of knowledge about ancient Israel. It tells us that Abraham
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Israelites from Mesopotamia to the mountains of Canaan, where they
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Moses, the Israelites’ new leader, parted the Red Sea and led his
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        tribes of Israel conquered all the lands north and south of Jerusalem,
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Israel; the south was called Judah. In its Greek form, Judea, it was
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        In about 1023 b.c. , the chiefs of the tribes of Israel
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        rivers Nile and the Euphrates were part of the Kingdom of Israel.
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        tribes. In about 721 b.c. , the north (Israel) was invaded and
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        devastated by Assyrians. The tribes of Israel were then scattered to
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        overthrown, and the Israelites returned to their land, which was now
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        into Israel.
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        new State of Israel. Jerusalem, the most fiercely disputed real-estate,
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        The State of Israel
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Israel was proclaimed. Immediately the first Israel-Arab war erupted,
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        to broker a peace agreement. Israel’s boundaries were redrawn and
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        into east and west, under the control of Jordan and Israel
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Jewish settlers still flooded into Israel, and new
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        combined Israeli-French and British attack on Egypt, and the start of
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        the Sinai War. The outcome was further territorial gains for Israel
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        international pressure forced Israel to withdraw — with Egypt
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Arab-Israeli conflict flared. As Arab armies massed on the borders of
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Israel in 1967, the Israeli Air Force destroyed the air forces of
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        over in six days. Israel gained total control of Palestine, including
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Syria struck back at Israel in 1973, on the holiest day of the Jewish
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        year, Yom Kippur. Israel was caught off guard but held out on the
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Egypt and Israel made an important movement towards a
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        permanent peace between an Arab nation and Israel when they agreed to a
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Israeli army invaded southern Leba­non in 1982 to safeguard its
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        Organization. Israeli forces then penetrated north to bombard PLO
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        within Israel.
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        set off the Palestinian intifada (uprising) against the Israeli troops
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        More traumatic to the hard-bitten Israelis was the
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        effect was significant. The Israelis couldn’t even retaliate, being
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        representative of the Palestinian people) and the Israeli government.
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        November 1994 the PLO leader Yasser Arafat, the Israeli prime minister
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        to unrest and the Israeli government watches cautiously to see if
written_2/travel_guides/berlitz1/HistoryIsrael.txt:        by Israeli land seizures. For visitors the peace dividend is currently
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        allotted to any of the twelve rival tribes of Israel, David made it the
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        his death the empire collapsed, and the Israelite kingdom was divided
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        into two separate, impoverished, often warring nations: Israel, with
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        Israel and moved southward to besiege Jerusalem. Thanks to King
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        Israelites were permitted to return to Jerusalem in 539 b.c. The city
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        Modern Israel
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        The State of Israel was declared during this difficult
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        Israeli forces secured a land corridor connecting the city to the
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        Jerusalem was to be under Israeli control, and East Jerusalem
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        barbed wire, no Israeli or Jewish pilgrims were allowed to visit the
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:        days the city was completely in Israeli hands, and in two weeks it was
written_2/travel_guides/berlitz1/IntroIndia.txt:        to Israel when it was founded in the year 1948.
written_2/travel_guides/berlitz1/IntroIsrael.txt:        Israel and the Israelis
written_2/travel_guides/berlitz1/IntroIsrael.txt:        Israel is many things to many people: a land of hope,
written_2/travel_guides/berlitz1/IntroIsrael.txt:        Although Israel is only now 50 years old, the roots of its three prime
written_2/travel_guides/berlitz1/IntroIsrael.txt:        society, the State of Israel provides home to people from over 80
written_2/travel_guides/berlitz1/IntroIsrael.txt:        Israel. This is a land where different and sometimes conflicting
written_2/travel_guides/berlitz1/IntroIsrael.txt:        melting-pot as a “land of unlimited impossibilities,” Israel compresses
written_2/travel_guides/berlitz1/IntroIsrael.txt:        windsurfers, and many others. Israel is so compact you can cram enough
written_2/travel_guides/berlitz1/IntroIsrael.txt:        Israel a splendid place for leisurely sun-worshipping. In recent years
written_2/travel_guides/berlitz1/IntroIsrael.txt:        hospices, and restaurants. Israelis are delighted that people from
written_2/travel_guides/berlitz1/IntroIsrael.txt:        foreigner to understand the Israeli psyche. Possibly no other country
written_2/travel_guides/berlitz1/IntroIsrael.txt:        Israel. Yet, despite all the displacement and suffering, the settlers
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        Israeli forces captured the Old City in 1967.
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        their habits and Israeli women in military uniforms. In the bazaars
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        Jerusalem and Israel have undergone enormous change in a very short
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        time. At the end of Israel’s War of Independence in 1948, the nation’s
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        half-century of its existence, Israel has absorbed approximately 2.5
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        The population of Israel is today approximately 6 million,
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        primarily in Galilee and on Mount Carmel. Israel is facing major
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        The Jewish people in Israel are from many lands and differ
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        in culture, language, and customs. Some have lived in Israel for
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        Lithuania that were consumed by the Holocaust. Ashkenazi Israelis
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        Israel’s famous kibbutz movement, along with families who escaped from
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        Israelis from Argentina are famous for their beef
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        barbecues; many American Israelis lovingly celebrate Thanksgiving and
written_2/travel_guides/berlitz1/IntroJerusalem.txt:        origins, however, all native-born residents of Israel are called
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Shopping in Israel is as exotic or as straightforward as you
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        that you’ll find anywhere in Israel. The Old City souqs offer all
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Art: Israeli art, and particularly modern art, is of a very
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        shops of the Israel Museum and the Tel Aviv Museum of Art are also
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        are undeniably Israeli. Look out too for decorative yarmulkes (skull
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Israel may not appear to be an obvious place to go for a
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        to world-class scuba diving in the Red Sea. The Israelis’ own sporting
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        18-hole course in Israel, in Caesarea (tel. 06-361174).
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Hiking: Israelis are great hikers, and almost everywhere
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Protection of Nature in Israel (SPNI) offers environmental hiking tours
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        doubt the sporting highlight of Israel. This is one of the richest
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Department at the Ministry of Tourism (tel. 02-623 7311) or the Israel
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        archaeology-related expeditions through the Israel Archaeological
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Three venues regularly put on Israeli folklore shows. The
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        If you are keen to learn Israeli folk dancing, the Bicurei
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        7777). Opera lovers can enjoy the acclaimed New Israel Opera company
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        of Art, Shaul Hamelech Boulevard (tel. 03-696 1297). The Israel Ballet
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Israeli folklore shows staged in the hotels. If you prefer a livelier
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Children’s Israel
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Israeli museums are usually modern, lively places. The
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Diaspora Museum and Museum of Art in Tel Aviv and the Israel Museum in
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        The resorts on Israel’s west coast don’t particularly cater
written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Wildlife: There are no major zoos in Israel. Even so, the
written_2/travel_guides/berlitz1/WhereToEgypt.txt:        from a Crusader church in Acre (now Israel) when it was overrun by Arab
written_2/travel_guides/berlitz1/WhereToEgypt.txt:        between Egypt and Israel. Its northern deserts were a battleground in
written_2/travel_guides/berlitz1/WhereToEgypt.txt:        the Egypt-Israeli conflicts of the 1950s and 1960s, and it was occupied
written_2/travel_guides/berlitz1/WhereToEgypt.txt:        by Israel for many months before it passed permanently back into
written_2/travel_guides/berlitz1/WhereToEgypt.txt:        marking the Egyptian/Israeli border.
written_2/travel_guides/berlitz1/WhereToFrance.txt:        the kings of Judah and Israel have been remodeled after the drawings of
written_2/travel_guides/berlitz1/WhereToIndia.txt:        Israel was founded, a massive emigration left only dozens behind. The
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        Israel is a small country, measuring just 445 km (260 miles)
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        Jerusalem is the undisputed star attraction of Israel. And
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        The Israel Museum and Farther West
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        finest museum in the country, the Israel Museum. It’s a large complex,
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        to do this and the Israel Museum in a day, but students of Middle
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        A five-minute walk away is Israel’s Parliament, the
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        monument and a name (which shall not perish)” — is Israel’s Holocaust
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        perspective of modern Israel. Entrance to the museum complex is
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        is unacceptable to many Israelis). The designation of the name came
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        1950. Recaptured by Israel in 1967, it has become synonymous with the
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        tour group. Cars with Israeli license plates (including rented cars)
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        Tel Aviv is in many ways the epitome of the New Israel
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        Museum of Art houses an excellent collection of Israeli and European
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        two is Eretz Israel (the Land of Israel), spread out over small
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        quite possibly the finest museum in Israel and certainly the most
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        the Eretz Israel Museum.
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        With the possible exception of Tel Aviv, Israel is not
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        exclusively by Israeli citizens. Ashkelon is a site of great antiquity
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        founder of modern Zionism, is Israel’s most upmarket resort, with
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        centre of Israel’s diamond industry (see page 51).
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        This northwest corner of Israel has been relatively
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        the British blockade to smuggle immigrants into Israel. On the other
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        most rewarding places to visit in Israel. It has the colour and
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        City. His mosque is the third largest in Israel and the most important
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        the violent history of modern Israel, and ends in the Scaffold Room
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        five-minute walk to Hof Argaman (Purple Beach), one of Israel’s finest
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        The Galilee is Israel’s lushest landscape, with grassy
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        Tiberias became one of Israel’s four holy Jewish cities, along with
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        Syrian territory before 1967 — when Israel seized it in
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        Golan isn’t recognized as Israeli territory by the United Nations, but
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        A visit to Israel would not be complete without a trip
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        between Israel and Jordan. The Judean Desert is the lowest point on
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        on display in the excellent Shrine of the Book in the Israel Museum,
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        The name “Masada” (meaning “fortress”) is an Israeli
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        rallying call for freedom or death. Israeli schoolchildren make the
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        south — over half of Israel. The desert around highway 90 along the
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        is the finest panorama in Israel, seen from a modern eyrie set into the
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        77). Its Byzantine bath-house is one of the best preserved in Israel,
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        Israel, a purpose-built town that has sprung up from an isolated
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        ExcursionS beyond Israel
written_2/travel_guides/berlitz1/WhereToIsrael.txt:        are generally too far from Israel for most vacationers but the
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        on the western hills of the city, the dynamic Israel Museum, the
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        Israel.
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        Jews until reclaimed by Israeli forces in 1967. Since then, the Jewish
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        immigrated to Israel.
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        The Tiferet Israel Synagogue, also called Nisan Bek, was
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        Tiferet Israel was the tallest and perhaps the grandest synagogue in
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        posthumously honored by the State of Israel for saving the lives of a
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        Road toward the city is a small but dramatic monument to Israeli
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        Israel and swept its ten tribes from the annals of history. Without
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        the God of Israel. Today nothing remains of those altars.
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        the cease-fire, Israeli forces were allowed to remain in position on
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        places in East Jerusalem became inaccessible to Israelis, but a new
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        university library serves as Israel’s National Library. You’ll need to
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        Israel Museum, the Knesset (Israel’s Parliament), and the ministries
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        Jewish Agency. Offices are here also for Keren Hayesod (United Israel
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        Knesset, Israel’s parliament, meets in a modern building decorated with
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        are the pavilions of the extraordinary Israel Museum, which comprises
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        The university is one of Israel’s proudest achievements, where you will
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        people and events in Israel’s history. Mount Herzl is named after
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        whose vision aided the eventual establishment of the State of Israel
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        gardens nearby are the burial sites of other modern Israeli leaders,
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        masterpieces, each signifying one of the twelve tribes of Israel.
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        Judean mountains are two unique memorials to non-Israelis: the Kennedy
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        Nazareth is the major Arab city in Israel; its population comprises
written_2/travel_guides/berlitz2/Canada-WhereToGo.txt:From the Cité du Havre north of Victoria Bridge, the controversial apartment complex of Habitat, designed by the Israeli-born architect Moshe Safdie for Expo ’67, provides residents with a grandstand view of the river and its islands. What looks to some like the aftermath of a child’s tantrum among its building blocks is on closer inspection an artful composition of 354 precast concrete boxes (originally hoisted into place by crane) to create 158 homes of various sizes and combinations. To see the river from the river, take a harbor cruise from Quai Victoria, the northern most wharf in Vieux Montréal, at the foot of rue Berri. 
findresults.txt:written_2/travel_guides/berlitz1/HandRIsrael.txt
findresults.txt:written_2/travel_guides/berlitz1/HistoryIsrael.txt
findresults.txt:written_2/travel_guides/berlitz1/IntroIsrael.txt
findresults.txt:written_2/travel_guides/berlitz1/WhatToIsrael.txt
findresults.txt:written_2/travel_guides/berlitz1/WhereToIsrael.txt
grepresults.txt:written_2/travel_guides/berlitz1/HandRIsrael.txt
grepresults.txt:written_2/travel_guides/berlitz1/HistoryIsrael.txt
grepresults.txt:written_2/travel_guides/berlitz1/IntroIsrael.txt
grepresults.txt:written_2/travel_guides/berlitz1/WhatToIsrael.txt
grepresults.txt:written_2/travel_guides/berlitz1/WhereToIsrael.txt
```
Since grep -r searches recursively, it will output the text inside the files that have the key word ("Israel" in this case), and then output the file names that have the key word. In this example, after the line
```
written_2/travel_guides/berlitz2/Canada-WhereToGo.txt:From the Cité du Havre north of Victoria Bridge, the controversial apartment complex of Habitat, designed by the Israeli-born architect Moshe Safdie for Expo ’67, provides residents with a grandstand view of the river and its islands. What looks to some like the aftermath of a child’s tantrum among its building blocks is on closer inspection an artful composition of 354 precast concrete boxes (originally hoisted into place by crane) to create 158 homes of various sizes and combinations. To see the river from the river, take a harbor cruise from Quai Victoria, the northern most wharf in Vieux Montréal, at the foot of rue Berri. 
```
it then lists the file names with Israel in the file name, starting with 
```
findresults.txt:written_2/travel_guides/berlitz1/HandRIsrael.txt
```
I found out how the grep -r command line option works at this [link](https://www.computerhope.com/unix/ugrep.htm)
## grep -n command line option
This is the first example of the grep -n command option
```
[cs15lwi23aqw@ieng6-201]:skill-demo1-data:483$ grep -n "in fact" written_2/*/*/*/*
written_2/non-fiction/OUP/Abernathy/ch14.txt:17:Note that the information and manufacturing practices examined here are not specific to the apparel industry—in fact, most were originally introduced in other sectors—but are applicable to a wide variety of consumer product industries. We focus on the retail-apparel channel because HCTAR’s surveys provide extensive evidence for the ways in which apparel suppliers are changing. Even if suppliers in other businesses will not make the specific operational changes of an apparel-maker, an increasing number are establishing information links with other channel players and combining information use with technologies and work practices to speed up order processing. For example, textile firms that supply retailers directly with their own products may have to combine equivalent information technologies with manufacturing innovations in finishing lines that shorten production cycles in order to gain competitive advantage. Much of what we have learned about the determinants of success for apparel suppliers can be applied to comparable situations faced by businesses in other retail-driven industries.
written_2/non-fiction/OUP/Abernathy/ch2.txt:44:By organizing cutters first, unions gained the leverage with which they could then organize and represent the much larger, but less skilled, group of sewers who worked in factory settings, particularly in the men’s industry, or in the small shops that characterized the women’s industry. The principal architects of this approach, Sidney Hillman, founding president of the Amalgamated, and David Dubinsky, long-time president of the ILGWU, were cutters and came out of this craft-group.24
written_2/non-fiction/OUP/Abernathy/ch7.txt:44:Manufacturers—whether of suits, CDs, office products, or pasta—generally classify products in terms of product lines. Planning, therefore, is done for fall fashion lines, jazz ensemble CDs, yellow legal pads, or fettuccine pasta products. Even if this method of categorization is important from a marketing perspective, it often glosses over what is, in fact, common to many products that seem different and different about products that seem the same. Once again, demand variability is key. For our men’s suit manufacturer, the men’s size 43-regular coat may have less in common with the size 46-regular coat in the same size and color than with a fashionable boy’s blazer.
written_2/non-fiction/OUP/Abernathy/ch8.txt:8:Yet not every aspect of apparel production depends on new technologies; in fact, automated sewing processes and the use of robots on the apparel shop floor have not turned out to be profitable or effective.1 People do a better job than computers of adjusting fabric alignment through sewing machines and compensating for prior sewing and cutting errors. As a result, the marginal costs for human sewing operators are lower than those of the complex robotic systems needed to guide sewing of limp fabric in most operations.
written_2/non-fiction/OUP/Abernathy/ch8.txt:27:A typical marker for men’s pants is shown in Figure 8.1 (page 137). At first glance, it might appear that almost all of the cloth is used in the marker; in fact, only 90 percent has been covered in the layout of 108 individual pieces. Given the basic shapes of the pants pieces, it is unlikely that a substantial increase in marker efficiency can be achieved. At best, experience with different combinations of waist sizes and leg lengths for a given design allows a scheduler to aggregate the units to be made into groups of large and small sizes, which means marker-makers can achieve efficiencies near 90 percent for casual pants. Higher cloth utilization is possible with jeans, but lower levels are normal for blouses, jackets, and intimate apparel (see Figure 8.2).
written_2/non-fiction/OUP/Abernathy/ch8.txt:52:Like computer-controlled cutting equipment, large-capacity knit die-cutting presses are expensive machines; they can cost up to $400,000 and are generally found only in factories of the largest producers. The die is a razor-sharp steel outline of the desired item to be cut. Like a cookie cutter, it is pressed down on the fabric and, if all is aligned, a replica of the die is cut from the tube. To change the size of the item to be cut, the die must be removed and a new one installed. The machines are massive in size because they must be rigid to achieve cutting along the entire silhouette. Die-cutters are much safer when fully automated, but building computerized loading and unloading features into the machine adds cost. Therefore, such machines are used only where long production runs of a given size of T-shirt or sweatpants will allow a payback of their capital costs through round-the-clock or multi-shift operations.
written_2/non-fiction/OUP/Abernathy/ch9.txt:16:In a factory setting, lockstitch machines are used for the decorative stitching that is necessary whenever the undersurface of a garment piece will be seen during normal wear, such as in the collar and cuffs of a dress shirt. The primary disadvantage of this kind of machine is that the bobbin must be small enough so that it can pass through the top thread loop, but it then quickly empties of thread. When this happens, sewing must be stopped and a newly loaded bobbin inserted to replace the empty one. Since the bobbin is reached by sliding back the stitch plate, if a bobbin runs out in the middle of an operation, it might be necessary to rip the seam out from the beginning and start over. Therefore, sewing operators generally keep track of the number of items sewn on a bobbin and stop before the thread runs out. If it were not for the limited thread capacity of the bobbin and the need for the operator to wind thread onto the bobbin, the lockstitch would be more widely used in factory assembly operations.
written_2/non-fiction/OUP/Abernathy/ch9.txt:21:Nevertheless, the advantages of the chain-stitch machine far outweigh its disadvantages. A chain-stitch seam is strong and can be produced more quickly than a lockstitch seam. Most of the long seams in factory-sewn apparel are made with a chain-stitch machine or with variations of it. The felled seam commonly used for the inseam of jeans comes from a two-needle chain-stitch machine. Such stitching generally outlasts the fabric of jeans, as one can see from looking at the holey knees of jeans worn by many teenagers.
written_2/non-fiction/OUP/Abernathy/ch9.txt:23:A wide variety of specialized sewing machines are also used in factories. There are machines with multiple needles and loopers that attach elastic waistbands to boxer shorts, for example. Knit fleece goods are commonly joined by a seaming operation called over-edging in the factory (and overlocking sewing in home use). The over-edge or overlocking machine automatically aligns the fabric by trimming off the edges of the plies to be joined just before the stitch is made. At least one thread wraps around the edge of the fabric during the stitching process. There are one-, two-, three-, four-, and five-thread overlocking or over-edging machines, each one designed to meet a given requirement of seam, strength, flexibility, and security. Over-edge machines can run at more than 8,000 stitches a minute. At eight or ten stitches an inch, it is possible to seam thirteen to sixteen or more inches a second. In the factory, however, a sewing machine’s maximum speed is generally not what limits production; it is the time it takes to set up the work on the machine and guide the fabric to the needle as the seam is being made.
written_2/non-fiction/OUP/Berk/ch2.txt:169:Furthermore, interpretations of children’s misbehavior diered between the two cultures. Consistent with the Confucian parental obligation, “The deeper the love, the greater the correction,” Chinese mothers’ “misdeed” stories were much longer than those of the American mothers—in fact, the most lengthy and elaborate of all Chinese narrations. Sometimes they occurred right after the child committed a transgression; at other times, they reminded the child of earlier improper behavior. Chinese mothers typically corrected the child repeatedly: “What did you say?” “So, what would you say?” “Then how would Mom have reacted?” And in line with the Confucian reliance on formal stories with moral lessons, these informal narratives often ended with direct teaching of how to act: “Saying dirty words is not good,” and (after the child agreed) an expression of aection—a hug, a tender touch.
written_2/non-fiction/OUP/Castro/chB.txt:7:As the tale is often narrated, a disobedient young girl goes to the dance without her parents’ permission, or she goes against her mother’s express wishes. While at the dance a handsome beautifully dressed man asks her to dance. They dance all night, until she suddenly notices with a shock that he isn’t wearing shoes, and in fact he doesn’t even have feet; instead he has chicken feet, goat’s hooves, or a pig’s foot and a chicken foot. It is usually at this point, after he’s discovered, that he disappears into thin air, leaving the odor of sulfur in the air, or, in some versions of the legend, just runs out the door. The girl he was dancing with either faints or burns to death as she goes up in smoke. If the girl doesn’t die, as in some stories, she might suffer a burn on the shoulder or a man’s handprint might be found on her back. A small circle of people who are present at the dance observe this encounter, and the narrator of the story usually says that she or he heard it from someone who was there.
written_2/non-fiction/OUP/Castro/chM.txt:53:Theories about the origin of the word Mariachi are interesting. There is the idea that it evolved from María, the name of the mother of Jesus Christ. Another idea is that it comes from the French word for marriage. But it is likely that the etymology of the word is of an indigenous nature. Mariachi groups originated in the region of Jalisco, even before it was named as a state, a region greatly influenced by the Coca people, and in fact the Nahuatl word for contemporary indigenous performers is mariachitos.
written_2/non-fiction/OUP/Castro/chZ.txt:8:Even though the zoot suit was worn by the young men of several different races and ethnicities, it is primarily identified with the pachucos of Los Angeles. Pachucos were mostly second-generation Mexicans, the sons of migrant laborers and working-class immigrants. Pachucos created their own subculture, an arrogant style of dressing, a bilingual secret argot, and for some individuals membership in petty criminal gangs. The zoot suit became a symbolic disguise that identified the zoot-suiter as neither a Mexican nor an American. It was not a bicultural or binational position, but rather a position between cultures, a “hanging in space” position. The overly confident, slow swagger of the pachuco, today exemplified by the cholo, made it appear in fact as if the zoot-suiter were walking on air.
written_2/non-fiction/OUP/Fletcher/ch1.txt:50:This was a revolutionary change. The states were no longer the autonomous sovereigns that they thought they were when they claimed the right of secession. They were now, in fact, servants of their people. Governments existed to guarantee due process and equal justice for all. The local law was no longer simply a creature of the states. The states themselves were enmeshed in the law and subordinate to it.
written_2/non-fiction/OUP/Fletcher/ch1.txt:94:These words are, in fact, better known in the United States than the preamble to the first Constitution. Schoolchildren routinely recite them and thereby imbibe the intuition that these words defined America after the Civil War. Yet, because we know these resonant phrases, we rarely stop to listen and ponder the meaning of each well-crafted line. Let us now put ourselves among the crowd of mourners at Gettysburg. Let us transport ourselves back into the frame of mind of those suffering losses, those looking for the meaning of brothers slaughtering brothers.
written_2/non-fiction/OUP/Fletcher/ch10.txt:55:The first Constitution plays on the theme of distrust in government. We must secure our freedoms against potentially abusive officials seeking “rents” by pursuing their own bureaucratic interests.22 The second constitution presupposes trust in an aggressive government, a watchdog of transactions that might slide into the forbidden territory of “involuntary servitude.” In this regard, public opinion seems to be at odds with the de facto tolerance of Americans for governmental action that is becoming ever more intrusive. The public supposedly suffers from declining trust in government.23 Yet, in fact, the average person tolerates actions by government that can make sense only on the assumption that those potentially affected by governmental abuse see Washington officials as their allies in a common struggle. A good example is the census and the popular reaction. The census form for the year 2000, like several before it, poses probing questions about racial and ethnic identity. The government wants to know how many blacks and other minorities live in particular sections of the country. The questionnaire imposes a detailed grid of racial variations on people who might otherwise simply have thought of themselves as Americans or perhaps as “minorities.” This information becomes relevant, it is said, to Justice Department officials monitoring the distribution of voting power in congressional districts.24
written_2/non-fiction/OUP/Fletcher/ch5.txt:94:Black pursues the theme of freedom and ignores the phrase that in fact requires emphasis in reading Lincoln: a new birth of freedom. The redemption and renaissance of our country would become possible only by confronting our “offences,” and that meant recognizing and compensating for the evil of slavery. The issue that could stimulate a new birth of the nation, therefore, was not freedom itself but freedom tempered by equality before the law.
written_2/non-fiction/OUP/Fletcher/ch6.txt:115:The Constitution became what the courts do in fact. Legalism prevailed. The legal philosophy of the Confederacy triumphed, both in substance and in style.55 The ideals of Gettysburg became, for the lawyers in the second half of the nineteenth century, a matter of history. For the nation as a whole, however, the values of Gettysburg—nationhood, equality, and democracy—retained their promise, and these principles would eventually return to the field of litigated law.
written_2/non-fiction/OUP/Fletcher/ch9.txt:5:In recent years, the Secret Constitution has come to assert itself in the opinions, particularly the dissenting opinions, of the Supreme Court. If we are to understand the impact of our implicit postbellum commitment to the ideas of nationhood, democracy, and equality, we cannot limit ourselves to the jurisprudence of the nine justices who happen to sit on the Court in Washington. The Secret Constitution has, in fact, a much deeper grounding in American political and legal culture, and it has come to express itself in diverse arenas. It spontaneously percolates through civil society. It shapes the process of constitutional amendment; indeed, virtually every constitutional amendment enacted since the Civil War expresses, in one way or another, the values of the Secret Constitution. This is true as well of the two leading proposed constitutional amendments that have gained a large political following in the last decade: the proposal to protect the flag against “desecration” and the movement to protect victims of crime. The values of the Secret Constitution have also found their way into subconstitutional federal legislation based, as a technical matter, on the Interstate Commerce Clause, granting Congress authority to regulate commerce “among the states.”1 The earlier defeat in the Supreme Court of the Civil Rights Act of 1866 meant that Congress had to find other means of bringing to bear the same set of values in the pursuit of equal treatment in public facilities and in the workplace. In order to see the resurgence of the three great ideas of the Secret Constitution—nationhood, democracy, and equality—we have to look afield, away from the courts, to these diverse areas that give birth to legal trends and define the bedrock of the American Constitution.2
written_2/non-fiction/OUP/Kauffman/ch1.txt:7:ecturing in Dublin, one of the twentieth century’s most famous physicists set the stage of contemporary biology during the war-heavy year of 1944. Given Erwin Schrödinger’s towering reputation as the discoverer of the Schrödinger equation, the fundamental formulation of quantum mechanics, his public lectures and subsequent book were bound to draw high attention. But no one, not even Schrödinger himself, was likely to have foreseen the consequences. Schrödinger’s What Is Life? is credited with inspiring a generation of physicists and biologists to seek the fundamental character of living systems. Schrödinger brought quantum mechanics, chemistry, and the still poorly formulated concept of “information” into biology. He is the progenitor of our understanding of DNA and the genetic code. Yet as brilliant as was Schrödinger’s insight, I believe he missed the center. Investigations seeks that center and finds, in fact, a mystery.
written_2/non-fiction/OUP/Kauffman/ch1.txt:43:All free-living cells are, by this definition, autonomous agents. To take a simple example, our bacterium with its flagellar motor rotating and swimming upstream for dinner is, in point of plain fact, a self-reproducing molecular system that is carrying out one or more thermodynamic work cycles. So is the paramecium chasing the bacterium, hoping for its own dinner. So is the dinoflagellate hunting the paramecium sneaking up on the bacterium. So are the flower and flatworm. So are you and I.
written_2/non-fiction/OUP/Kauffman/ch1.txt:97:Might collective autocatalysis of proteins or similar polymers be the basic source of self-reproduction in molecular systems? Or must life be based on template replication, as envisioned by Watson and Crick, or as envisioned even earlier by Schrödinger in his aperiodic solid with its microcode? In view of the potential for a general biology, what, in fact, are the alternative bases for self-reproducing molecular systems here and anywhere in the cosmos? Which of these alternatives is more probable, here and anywhere?
written_2/non-fiction/OUP/Kauffman/ch10.txt:14:It is not obvious, in fact, that the universe should be complex. One can imagine universes governed by general relativity that burst briefly into big bang being, then recollapse in a rapid big crunch within parts of a second or a century. Alternatively, one can imagine universes governed by general relativity that burst into big bang being and expanded forever with no further complexity than hydrogen and helium and smaller particles in an open and ever-expanding dark, cold vastness.
written_2/non-fiction/OUP/Kauffman/ch10.txt:18:Why the universe is complex rather than simple is, in fact, beginning to emerge as a legitimate and deep question. In the past several years, I have had the pleasure to come to know Lee Smolin, whose career is devoted to quantum gravity and cosmology. Most of what I shall write in this chapter reflects my conversations and work with Lee and his colleagues, who have been wonderfully welcoming to this biologist. Sometimes outsiders can make serious contributions. Sometimes outsiders just make damned fools of themselves.
written_2/non-fiction/OUP/Kauffman/ch10.txt:41:To understand the core of decoherence, one must understand that the exhibition of interference phenomena, the hallmark of quantum mechanics noted in the double-slit photon experiment, requires that literally all the propagating possible pathways in Feynman’s sum over histories that are to arrive at each point on the photon-counter surface, do in fact arrive at that point. If some fail to arrive, the sum over all histories fails. In eect, if some of the phase information, the core of constructive and destructive interference, has been lost in the maze of interactions of the quantum system with its environment, then that phase information cannot come to be reassembled to give rise to quantum interference.
written_2/non-fiction/OUP/Kauffman/ch10.txt:99:As is known qualitatively by many outside the confines of the physics community, string theory began by giving up the picture of fundamental particles as zero-dimensional, point particles. In its initial version, in the place of point particles, string theory posited one-dimensional strings that might be open, with two ends, or closed loops, with no free ends. Among the fundamental ideas of string theory is the idea that the dierent particles and the dierent forces can all be thought of as dierent modes of vibration of such strings. Because strings have finite length, string theory can hope to overcome the infinities that emerge when attempts are made to marry point particle quantum theories with general relativity in a continuous space-time. In eect, the finite length of the strings prevents consideration of space becoming infinitely curved at a point. Thus, string theory can dream of uniting quantum mechanics and general relativity, and it has, in fact, produced the entity carrying the gravitational force, the graviton, in a natural way.
written_2/non-fiction/OUP/Kauffman/ch3.txt:106:The main conclusion to draw from our simulation is that autonomous agents coupling one or more autocatalytic and work cycles are a perfectly reasonable, if novel, form of nonequilibrium, open chemical reaction network. There is no hocus pocus here. In the near future we will almost certainly construct such autonomous-agent molecular reaction networks and study their dynamics and evolutionary behavior. A general biology is, in fact, around the corner.
written_2/non-fiction/OUP/Kauffman/ch3.txt:115:I turn, in the final section of this chapter, to yet another puzzle concerning what I call a natural game. A natural game is a way of making a living in an environment. That is, autonomous agents are able to act on their own behalf and regularly do so in order to make a living in an environment. The bacterium swimming upstream in a glucose gradient is making a living in its environment. So, in fact, are all free-living entities in the biosphere.
written_2/non-fiction/OUP/Kauffman/ch3.txt:121:Then how is it that in our biosphere we should find a family of landscapes that happen to be well searched by recombination? Either such smooth landscapes are built into the physical nature of things or evolution has itself somehow brought forth the very kinds of landscapes that are well searched by mutation and recombination. Restated, assuming that mutation and recombination are, in fact, good search procedures for the kinds of fitness landscapes inhabited by we mere mortals as we were hanging around and adaptively hill climbing for the past four billion years, I ask again: Whence these wonderful fitness landscapes that are so well suited to be climbed by mutation and recombination?
written_2/non-fiction/OUP/Kauffman/ch3.txt:128:And the central factors underlying that buildup of organization are the same factors that apply in an economy = that merely human extension of biospheres. The central factors, in fact, center on “advantages of trade.” We can see this keystone concept by supposing that you and I are the only members of a tiny economy. You begin life with an endowment of a thousand pears and a hundred apples. I begin life with an endowment of a hundred pears and a thousand apples. Suppose your happiness, or “utility,” would increase if you had fewer rather than more pears and more rather than fewer apples. Alas, you have more pears than apples. I, in turn, happen to have desires such that I would be happier with rather more pears than apples. Alas, I have more apples than pears.
written_2/non-fiction/OUP/Kauffman/ch3.txt:139:And note with the plant root and the fungi, thermodynamic work has been done by the plant to synthesize the sugars from sunlight, water, and carbon dioxide, and thermodynamic work has been done by the fungi to fix nitrogen from the air into amino acids. In a real biosphere, the linking of exergonic to endergonic reactions by which thermodynamic work is done to build up complex organization is, in fact, inextricably linked with the emergence of new advantages of trade = new, enhanced ways to make livings in new niches. In the present case, the exchange of sugar and amino acids helps both plant and fungi reproduce more rapidly.
written_2/non-fiction/OUP/Kauffman/ch4.txt:14:After exploring Maxwell’s demon, I will ask a physicist’s question, What is work? Physicists have an answer  work is force acting through distance  given by a single number, or scalar, representing the sum of the force acting through the distance. But it will turn out that in any specific case of work, the specific process is organized in some specific way. Work is more than force acting through distance; it is, in fact, the constrained release of energy, the release of energy into a small number of degrees of freedom. It is the constraints themselves  with, as Phil Anderson points out, a kind of rigidity  that largely constitute the organization of the process. But  and here will be the hook  in many cases it takes work to construct the constraints themselves. So we will come to a terribly important circle, work is the constrained release of energy, but it often takes work to construct the constraints.
written_2/non-fiction/OUP/Kauffman/ch4.txt:40:One resolution to this confusion has been suggested by Rolf Sinclair and Wojciech Zurek, who have returned to the demon problem with a wonderful set of concepts. When the demon has at it with the flap valve, he is, in fact, performing measurements on the gas system. As he performs the measurements, he “knows” more about the detailed state of the system. Now just what might it mean to know about the gas system? One useful sense of “know” is that the demon has some compact description of the state of the gas system. Indeed, the compact description of the equilibrium state is about as compact as you can get: A few macroscopic variables  temperature, pressure, volume  suce.
written_2/non-fiction/OUP/Kauffman/ch4.txt:51:We have, in fact, no answer as yet.
written_2/non-fiction/OUP/Kauffman/ch4.txt:83:Does it always take work to construct constraints? No, as we will soon see. Does it often take work to construct constraints? Yes. In those cases, the work done to construct constraints is, in fact, another coupling of spontaneous and nonspontaneous processes. But this is just what we are suggesting must occur in autonomous agents. In the universe as a whole, exploding from the big bang into this vast diversity, are many of the constraints on the release of energy that have formed due to a linking of spontaneous and nonspontaneous processes? Yes. What might this be about? I’ll say it again. The universe is full of sources of energy. Nonequilibrium processes and structures of increasing diversity and complexity arise that constitute sources of energy and that measure, detect, and capture those sources of energy, build new structures that constitute constraints on the release of energy, and hence drive nonspontaneous processes to create more such diversifying and novel processes, structures, and energy sources.
written_2/non-fiction/OUP/Kauffman/ch4.txt:87:In Figure .b I exhibit a device  a Rube Goldberg device, in fact  of which I am extremely proud. The same cannon as in .a now fires the same cannonball, which, however, hits a paddle on a sturdy paddle wheel I constructed. Once struck by the cannonball, the paddle wheel is set to spinning. Prior to my firing the cannonball, I contrived to tie one end of a red rope around the axle of the paddle wheel and a modest size bucket to the other end of the rope. Thereafter, I dropped the bucket down the well. The water-filled bucket has now rested, silent and waiting, until the cannonball strikes the paddle wheel, whereupon the wheel spins, the red rope winds up, pulling the water-filled bucket up the well, up against the axle, which tilts the bucket over  you will have to imagine this part  and pours the water into a long funnel that slopes down from the wellhead toward my bean field. When the water from the bucket arrives at the bottom of the water pipe, it pushes against a flap valve, thereby opening the valve and watering my bean field. You can see why I might be proud of my machine.
written_2/non-fiction/OUP/Kauffman/ch4.txt:94:Figure . is a schematic representation of a cell. The figure shows a typical bilipid membrane, small organic molecules of dierent species, A, B, C, D, E, F, G, a transmembrane channel, and so forth. Now, in fact, your cell typically does thermodynamic work to build up lipids from smaller molecular species. Typically, the energy is supplied by breakdown of ATP to ADP or similar exergonic reactions in metabolism. But lipids have the capacity to fall to a low energy structure, which is precisely a bilipid layer. As noted in chapter , lipids are molecules with a hydrophobic tail and a hydrophilic head. The hydrophilic head, as the name implies, likes water. Consequently, in an aqueous environment lipids will tend to form bilipid membranes with the hydrophilic heads facing the aqueous medium and the hydrophobic tails buried next to one another, away from the water. In fact, if you take some cholesterol, or another lipid or lipidlike molecule, and dissolve it in water, bilayer membrane vesicles form spontaneously that are called liposomes. So, your cells do thermodynamic work to make lipids, which spontaneously form a low-energy structure, the membrane.
written_2/non-fiction/OUP/Kauffman/ch4.txt:97:But the alteration in potential energy heights along the three dierent reaction pathways from A and B is precisely the alteration of the constraints on these reactions. The barrier heights, together with the even higher energy barriers that provide the walls of the reaction coordinates along which the reaction proceeds, constitute the constraints. So, in fact, the cell has actually done thermodynamic work to construct constraints on the release of chemical energy stored in A and B, that might be released to form C and D or E or F and G.
written_2/non-fiction/OUP/Kauffman/ch4.txt:107:If we do not yet understand organization fully, we can at least think about what happens in autonomous agents such as real cells. A real cell, a real molecular autonomous agent, does in fact carry out self-reproduction. In addition, it carries out one or more real work cycles, linking spontaneous and nonspontaneous processes. It does, in fact, measure, detect, and record sources of energy and does do work to construct constraints on the release of energy, which when released in the constrained way, propagates to do more work, often constructing further constraints on the release of energy or doing work by driving further nonspontaneous processes. Cells do achieve propagating work.
written_2/non-fiction/OUP/Kauffman/ch4.txt:114:Although my discussion above about organization is still preliminary, the basic points seem correct. A coevolving mixed microbial community that existed some three billion years ago, diversifying and coevolving via Darwinian mutation, recombination, and natural selection, did, in fact, measure and detect and create an increasing variety of energy sources, did, in fact, couple those detected energy sources into work cycles and other activities, and did, in fact, build a biosphere. Self-constructing organization did and does propagate. Our globe is covered by this propagating organization  life and its consequences.
written_2/non-fiction/OUP/Kauffman/ch6.txt:38:Remember, a propagating organization that builds itself and persistently ramifies in a nonequilibrium setting is not yet a concept that we understand. We have matter, energy, and entropy, but no clear notion of propagating organization in the sense we here struggle to articulate. And because the way a biosphere gets on with constructing itself may not be algorithmic, it may be that story is part of how we must, in fact, make sense of the persistent emergence of novelty in the biosphere.
written_2/non-fiction/OUP/Kauffman/ch6.txt:99:But what if we cannot prestate the configuration space of a biosphere? In that case, the way Newton taught us to do science is not the whole story. We cannot calculate as he did. And, in fact, biologists do not often do science as Newton taught. We carry on an odd mixture of historical analysis of the actual branching pathways of evolution; a dollop of theory about evolutionary landscapes, molecular evolution and coevolution, and ecosystems; and a lot of detailed experimental work to understand how actual creatures develop, how their life cycles unfold, how they assemble into ecosystems, and so forth.
written_2/non-fiction/OUP/Kauffman/ch7.txt:11:The aim of the current chapter is to explore the profound failure, on the scale of a suciently large closed thermodynamic system and, a fortiori, the open system of the biosphere, to come close to equilibrium on vastly long time scales with respect to the lifetime of the universe. The main facts are known to physicists, of course. The universe is vastly nonergodic above modest levels of molecular complexity, let alone with respect to gross motions of parts of the universe with respect to one another.
written_2/non-fiction/OUP/Kauffman/ch8.txt:123:In short, if we control for P classes, there is a very strong and very statistically significant residual bias toward high numbers of canalyzing inputs per gene. Conversely, when we controlled for canalyzing input classes and tested for a residual bias toward high P values, there was no sign whatsoever of such a bias. Thus, it appears that evolution has, in fact, tuned the choices of Boolean rules used to govern genes with K = and K = known inputs, as well as genes with K = and K = inputs that we have sampled, sharply in favor of a high bias toward usage of Boolean rules that are canalyzing functions.
written_2/non-fiction/OUP/Kauffman/ch8.txt:149:A final numerical test is under way. The aim of the numerical test is to check whether cells and communities that lie at the phase transition would, in fact, make the maximum number of reliable discriminations and act without trembling hands.
written_2/non-fiction/OUP/Kauffman/ch8.txt:156:Power law distributions can, in fact, arise in many ways. One of those ways is at a phase transition, for example, in a ferromagnet at the phase transition temperature. Above the phase transition temperature, the magnetic spins line up randomly with one another and keep flipping. Below the phase transition temperature, the ferromagnet tends to line up with magnetic spins all pointing the same way, say, north pole upward, hence, the material is magnetized. At the phase transition temperature, something magic and “universal” occur: clusters of spins oriented the same way arise, and the clusters have a power law distribution of sizes. The power law distribution implies that there is no preferred size scale in the system. If there were a preferred size scale, clusters would be distributed exponentially in size, setting a size scale at which clusters at that size were half as likely as tiny clusters of spins.
written_2/non-fiction/OUP/Kauffman/ch9.txt:42:Rational expectations grew, in part, out of an attempt to understand actual trading on stock exchanges. Under general competitive equilibrium, little trading should occur and stock prices should hover in the vicinity of their fundamental value, typically understood as the discounted present value of the future revenue stream from the stock. But, in fact, abundant trading does occur, and speculative bubbles and crashes occur. Rational expectations theory is built up around another fixed-point theorem. Rational expectations theory assumes a set of economic agents with beliefs about how the economy is working. The agents base their economic actions on those beliefs. A fixed point can exist under which the actions of the agents, given their beliefs about the economy, exactly create the expected economic behavior. So, under rational expectations one can understand bubbles. It is rational to believe that prices are going above fundamental value and thus to invest, and the investments sustain the bubble for a period of time.
written_2/non-fiction/OUP/Kauffman/ch9.txt:65:Bios Group Inc., the partnership with Ernst and Young, is now just three-and-a-half years old. We have grown to over seventy people, heading, we hope, for a hundred. Our annual revenues are running at $ million. We have a hopeful eye on $ to $ million this year with clients ranging from Texas Instruments, for whom we invented a novel adaptive chip, to the U.S. Marine Corps with its concern for adaptive combat, to Unilever, the NASDAQ stock market, Honda, Boeing, Johnson and Johnson, Procter & Gamble, Kellogg, Southwest Airlines, the Joint Chiefs of Sta, and others. We have spun out a biotechnology company, CIStem Molecular, that aims to clone the small cis acting DNA regions that control turning genes on and o in development and disease; a European daughter company, Euro-Bios; as well as EXA, a company spun out with NASDAQ to make tools for financial markets. I’m deeply glad to be chairman of the board and chief scientist of Bios, to be working with a very creative group of colleagues, and to be finding routes in the practical world where our ideas do, in fact, apply.
written_2/non-fiction/OUP/Kauffman/ch9.txt:155:But Figure . gives us an intuitive understanding of Unilever’s problem, in fact, the problem is far more general than Unilever’s assembly plants. Think of each clause, (A v A), et cetera, as a way to make one of the toothpaste products, and think of the conjunction, (A v A) and (A v A) and   .   .   .   , as the way to make all twenty-seven toothpastes. Then as the number of clauses, hence toothpaste products, increases for a given plant with V variables to use in making these dierent products, all of a sudden the conjoint problem will have so many conflicting constraints that it will cross the phase transition from solvable to insolvable.
written_2/non-fiction/OUP/Kauffman/ch9.txt:172:We as organisms have, in fact, constructed our ways of making a living such that those problem spaces are typically, but not always, solvable as coevolution proceeds. And, on average, the same thing holds for the econosphere. As old ways of making a living go extinct, new ones persistently enter. We too, it appears, have coconstructed our econosphere such that our ways of making a living, and discovering new ways of making a living, are manageable, probably in a self-organized critical manner, with small and large speciation and extinction events.
```
In the example above, we see that the grep -n command option will search a specific phrase in a text file and return the line containing the phrase, as well as the line number in the text file the phrase was contained in. 
This is the second example of the grep -n command.
```
[cs15lwi23aqw@ieng6-201]:skill-demo1-data:486$ grep -n "Lucayans" written_2/*/*/*
grep: written_2/non-fiction/OUP/Abernathy: Is a directory
grep: written_2/non-fiction/OUP/Berk: Is a directory
grep: written_2/non-fiction/OUP/Castro: Is a directory
grep: written_2/non-fiction/OUP/Fletcher: Is a directory
grep: written_2/non-fiction/OUP/Kauffman: Is a directory
grep: written_2/non-fiction/OUP/Rybczynski: Is a directory
written_2/travel_guides/berlitz2/Bahamas-History.txt:6:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
written_2/travel_guides/berlitz2/Bahamas-History.txt:7:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
```
We see that grep -n command option doesn't work directories, and so the first six lines are outputed when it tries to search through a directory. Then, it lists out the two spots where "Lucayans" is present in a text file, and we see that they are in lines 6 and 7 in the Bahamas-History.txt file. 
I found out how the grep -n command line option works at this [link](https://www.geeksforgeeks.org/grep-command-in-unixlinux/)
## grep -c command option
This is the first example of the grep -c command.
```
[cs15lwi23aqw@ieng6-201]:skill-demo1-data:500$ grep -c "Lucayans" written_2/*/*/*    
grep: written_2/non-fiction/OUP/Abernathy: Is a directory
written_2/non-fiction/OUP/Abernathy:0
grep: written_2/non-fiction/OUP/Berk: Is a directory
written_2/non-fiction/OUP/Berk:0
grep: written_2/non-fiction/OUP/Castro: Is a directory
written_2/non-fiction/OUP/Castro:0
grep: written_2/non-fiction/OUP/Fletcher: Is a directory
written_2/non-fiction/OUP/Fletcher:0
grep: written_2/non-fiction/OUP/Kauffman: Is a directory
written_2/non-fiction/OUP/Kauffman:0
grep: written_2/non-fiction/OUP/Rybczynski: Is a directory
written_2/non-fiction/OUP/Rybczynski:0
written_2/travel_guides/berlitz1/HandRHawaii.txt:0
written_2/travel_guides/berlitz1/HandRHongKong.txt:0
written_2/travel_guides/berlitz1/HandRIbiza.txt:0
written_2/travel_guides/berlitz1/HandRIsrael.txt:0
written_2/travel_guides/berlitz1/HandRIstanbul.txt:0
written_2/travel_guides/berlitz1/HandRJamaica.txt:0
written_2/travel_guides/berlitz1/HandRJerusalem.txt:0
written_2/travel_guides/berlitz1/HandRLakeDistrict.txt:0
written_2/travel_guides/berlitz1/HandRLasVegas.txt:0
written_2/travel_guides/berlitz1/HandRLisbon.txt:0
written_2/travel_guides/berlitz1/HandRLosAngeles.txt:0
written_2/travel_guides/berlitz1/HandRMadeira.txt:0
written_2/travel_guides/berlitz1/HandRMadrid.txt:0
written_2/travel_guides/berlitz1/HandRMallorca.txt:0
written_2/travel_guides/berlitz1/HistoryDublin.txt:0
written_2/travel_guides/berlitz1/HistoryEdinburgh.txt:0
written_2/travel_guides/berlitz1/HistoryEgypt.txt:0
written_2/travel_guides/berlitz1/HistoryFWI.txt:0
written_2/travel_guides/berlitz1/HistoryFrance.txt:0
written_2/travel_guides/berlitz1/HistoryGreek.txt:0
written_2/travel_guides/berlitz1/HistoryHawaii.txt:0
written_2/travel_guides/berlitz1/HistoryHongKong.txt:0
written_2/travel_guides/berlitz1/HistoryIbiza.txt:0
written_2/travel_guides/berlitz1/HistoryIndia.txt:0
written_2/travel_guides/berlitz1/HistoryIsrael.txt:0
written_2/travel_guides/berlitz1/HistoryIstanbul.txt:0
written_2/travel_guides/berlitz1/HistoryItaly.txt:0
written_2/travel_guides/berlitz1/HistoryJamaica.txt:0
written_2/travel_guides/berlitz1/HistoryJapan.txt:0
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:0
written_2/travel_guides/berlitz1/HistoryLakeDistrict.txt:0
written_2/travel_guides/berlitz1/HistoryLasVegas.txt:0
written_2/travel_guides/berlitz1/HistoryMadeira.txt:0
written_2/travel_guides/berlitz1/HistoryMadrid.txt:0
written_2/travel_guides/berlitz1/HistoryMalaysia.txt:0
written_2/travel_guides/berlitz1/HistoryMallorca.txt:0
written_2/travel_guides/berlitz1/IntroDublin.txt:0
written_2/travel_guides/berlitz1/IntroEdinburgh.txt:0
written_2/travel_guides/berlitz1/IntroEgypt.txt:0
written_2/travel_guides/berlitz1/IntroFWI.txt:0
written_2/travel_guides/berlitz1/IntroFrance.txt:0
written_2/travel_guides/berlitz1/IntroGreek.txt:0
written_2/travel_guides/berlitz1/IntroHongKong.txt:0
written_2/travel_guides/berlitz1/IntroIbiza.txt:0
written_2/travel_guides/berlitz1/IntroIndia.txt:0
written_2/travel_guides/berlitz1/IntroIsrael.txt:0
written_2/travel_guides/berlitz1/IntroIstanbul.txt:0
written_2/travel_guides/berlitz1/IntroItaly.txt:0
written_2/travel_guides/berlitz1/IntroJamaica.txt:0
written_2/travel_guides/berlitz1/IntroJapan.txt:0
written_2/travel_guides/berlitz1/IntroJerusalem.txt:0
written_2/travel_guides/berlitz1/IntroLakeDistrict.txt:0
written_2/travel_guides/berlitz1/IntroLasVegas.txt:0
written_2/travel_guides/berlitz1/IntroLosAngeles.txt:0
written_2/travel_guides/berlitz1/IntroMadeira.txt:0
written_2/travel_guides/berlitz1/IntroMadrid.txt:0
written_2/travel_guides/berlitz1/IntroMalaysia.txt:0
written_2/travel_guides/berlitz1/IntroMallorca.txt:0
written_2/travel_guides/berlitz1/JungleMalaysia.txt:0
written_2/travel_guides/berlitz1/WhatToDublin.txt:0
written_2/travel_guides/berlitz1/WhatToEdinburgh.txt:0
written_2/travel_guides/berlitz1/WhatToEgypt.txt:0
written_2/travel_guides/berlitz1/WhatToFWI.txt:0
written_2/travel_guides/berlitz1/WhatToFrance.txt:0
written_2/travel_guides/berlitz1/WhatToGreek.txt:0
written_2/travel_guides/berlitz1/WhatToHawaii.txt:0
written_2/travel_guides/berlitz1/WhatToHongKong.txt:0
written_2/travel_guides/berlitz1/WhatToIbiza.txt:0
written_2/travel_guides/berlitz1/WhatToIndia.txt:0
written_2/travel_guides/berlitz1/WhatToIsrael.txt:0
written_2/travel_guides/berlitz1/WhatToIstanbul.txt:0
written_2/travel_guides/berlitz1/WhatToItaly.txt:0
written_2/travel_guides/berlitz1/WhatToJamaica.txt:0
written_2/travel_guides/berlitz1/WhatToJapan.txt:0
written_2/travel_guides/berlitz1/WhatToLakeDistrict.txt:0
written_2/travel_guides/berlitz1/WhatToLasVegas.txt:0
written_2/travel_guides/berlitz1/WhatToLosAngeles.txt:0
written_2/travel_guides/berlitz1/WhatToMadeira.txt:0
written_2/travel_guides/berlitz1/WhatToMalaysia.txt:0
written_2/travel_guides/berlitz1/WhatToMallorca.txt:0
written_2/travel_guides/berlitz1/WhereToDublin.txt:0
written_2/travel_guides/berlitz1/WhereToEdinburgh.txt:0
written_2/travel_guides/berlitz1/WhereToEgypt.txt:0
written_2/travel_guides/berlitz1/WhereToFWI.txt:0
written_2/travel_guides/berlitz1/WhereToFrance.txt:0
written_2/travel_guides/berlitz1/WhereToGreek.txt:0
written_2/travel_guides/berlitz1/WhereToHawaii.txt:0
written_2/travel_guides/berlitz1/WhereToHongKong.txt:0
written_2/travel_guides/berlitz1/WhereToIbiza.txt:0
written_2/travel_guides/berlitz1/WhereToIndia.txt:0
written_2/travel_guides/berlitz1/WhereToIsrael.txt:0
written_2/travel_guides/berlitz1/WhereToIstanbul.txt:0
written_2/travel_guides/berlitz1/WhereToItaly.txt:0
written_2/travel_guides/berlitz1/WhereToJapan.txt:0
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:0
written_2/travel_guides/berlitz1/WhereToLakeDistrict.txt:0
written_2/travel_guides/berlitz1/WhereToLosAngeles.txt:0
written_2/travel_guides/berlitz1/WhereToMadeira.txt:0
written_2/travel_guides/berlitz1/WhereToMadrid.txt:0
written_2/travel_guides/berlitz1/WhereToMalaysia.txt:0
written_2/travel_guides/berlitz1/WhereToMallorca.txt:0
written_2/travel_guides/berlitz2/Algarve-History.txt:0
written_2/travel_guides/berlitz2/Algarve-Intro.txt:0
written_2/travel_guides/berlitz2/Algarve-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Algarve-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Amsterdam-History.txt:0
written_2/travel_guides/berlitz2/Amsterdam-Intro.txt:0
written_2/travel_guides/berlitz2/Amsterdam-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Amsterdam-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Athens-History.txt:0
written_2/travel_guides/berlitz2/Athens-Intro.txt:0
written_2/travel_guides/berlitz2/Athens-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Athens-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Bahamas-History.txt:2
written_2/travel_guides/berlitz2/Bahamas-Intro.txt:0
written_2/travel_guides/berlitz2/Bahamas-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bahamas-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Bali-History.txt:0
written_2/travel_guides/berlitz2/Bali-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bali-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Barcelona-History.txt:0
written_2/travel_guides/berlitz2/Barcelona-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Barcelona-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Beijing-History.txt:0
written_2/travel_guides/berlitz2/Beijing-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Beijing-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Berlin-History.txt:0
written_2/travel_guides/berlitz2/Berlin-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Berlin-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Bermuda-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bermuda-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Bermuda-history.txt:0
written_2/travel_guides/berlitz2/Boston-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Budapest-History.txt:0
written_2/travel_guides/berlitz2/Budapest-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Budapest-WhereoGo.txt:0
written_2/travel_guides/berlitz2/California-History.txt:0
written_2/travel_guides/berlitz2/California-WhatToDo.txt:0
written_2/travel_guides/berlitz2/California-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Canada-History.txt:0
written_2/travel_guides/berlitz2/Canada-WhereToGo.txt:0
written_2/travel_guides/berlitz2/CanaryIslands-History.txt:0
written_2/travel_guides/berlitz2/CanaryIslands-WhatToDo.txt:0
written_2/travel_guides/berlitz2/CanaryIslands-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Cancun-History.txt:0
written_2/travel_guides/berlitz2/Cancun-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Cancun-WhereToGo.txt:0
written_2/travel_guides/berlitz2/China-History.txt:0
written_2/travel_guides/berlitz2/China-WhatToDo.txt:0
written_2/travel_guides/berlitz2/China-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Costa-History.txt:0
written_2/travel_guides/berlitz2/Costa-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Costa-WhereToGo.txt:0
written_2/travel_guides/berlitz2/CostaBlanca-History.txt:0
written_2/travel_guides/berlitz2/CostaBlanca-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Crete-History.txt:0
written_2/travel_guides/berlitz2/Crete-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Crete-WhereToGo.txt:0
written_2/travel_guides/berlitz2/CstaBlanca-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Cuba-History.txt:0
written_2/travel_guides/berlitz2/Cuba-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Cuba-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Nepal-History.txt:0
written_2/travel_guides/berlitz2/Nepal-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Nepal-WhereToGo.txt:0
written_2/travel_guides/berlitz2/NewOrleans-History.txt:0
written_2/travel_guides/berlitz2/Paris-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Paris-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Poland-History.txt:0
written_2/travel_guides/berlitz2/Poland-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Portugal-History.txt:0
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Portugal-WhereToGo.txt:0
written_2/travel_guides/berlitz2/PuertoRico-History.txt:0
written_2/travel_guides/berlitz2/PuertoRico-WhatToDo.txt:0
written_2/travel_guides/berlitz2/PuertoRico-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Vallarta-History.txt:0
written_2/travel_guides/berlitz2/Vallarta-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Vallarta-WhereToGo.txt:0
```
We see that grep -c doesn't work on directories, but it works on files. It outputs how many times the key word/phrase ("Lucayans" in this case) is in a line within the file. We see that "Lucayans" doesn't come up in any other file but the Bahamas-History.txt file. 
This is the second example of the grep -c command option. 
```
[cs15lwi23aqw@ieng6-201]:skill-demo1-data:503$ grep -c "fact" written_2/travel_guides/berlitz2/*
written_2/travel_guides/berlitz2/Algarve-History.txt:1
written_2/travel_guides/berlitz2/Algarve-Intro.txt:0
written_2/travel_guides/berlitz2/Algarve-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Algarve-WhereToGo.txt:4
written_2/travel_guides/berlitz2/Amsterdam-History.txt:2
written_2/travel_guides/berlitz2/Amsterdam-Intro.txt:5
written_2/travel_guides/berlitz2/Amsterdam-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Amsterdam-WhereToGo.txt:5
written_2/travel_guides/berlitz2/Athens-History.txt:3
written_2/travel_guides/berlitz2/Athens-Intro.txt:2
written_2/travel_guides/berlitz2/Athens-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Athens-WhereToGo.txt:18
written_2/travel_guides/berlitz2/Bahamas-History.txt:4
written_2/travel_guides/berlitz2/Bahamas-Intro.txt:1
written_2/travel_guides/berlitz2/Bahamas-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bahamas-WhereToGo.txt:9
written_2/travel_guides/berlitz2/Bali-History.txt:0
written_2/travel_guides/berlitz2/Bali-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bali-WhereToGo.txt:4
written_2/travel_guides/berlitz2/Barcelona-History.txt:0
written_2/travel_guides/berlitz2/Barcelona-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Barcelona-WhereToGo.txt:4
written_2/travel_guides/berlitz2/Beijing-History.txt:0
written_2/travel_guides/berlitz2/Beijing-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Beijing-WhereToGo.txt:5
written_2/travel_guides/berlitz2/Berlin-History.txt:0
written_2/travel_guides/berlitz2/Berlin-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Berlin-WhereToGo.txt:3
written_2/travel_guides/berlitz2/Bermuda-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Bermuda-WhereToGo.txt:4
written_2/travel_guides/berlitz2/Bermuda-history.txt:1
written_2/travel_guides/berlitz2/Boston-WhereToGo.txt:7
written_2/travel_guides/berlitz2/Budapest-History.txt:0
written_2/travel_guides/berlitz2/Budapest-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Budapest-WhereoGo.txt:1
written_2/travel_guides/berlitz2/California-History.txt:3
written_2/travel_guides/berlitz2/California-WhatToDo.txt:0
written_2/travel_guides/berlitz2/California-WhereToGo.txt:4
written_2/travel_guides/berlitz2/Canada-History.txt:8
written_2/travel_guides/berlitz2/Canada-WhereToGo.txt:22
written_2/travel_guides/berlitz2/CanaryIslands-History.txt:0
written_2/travel_guides/berlitz2/CanaryIslands-WhatToDo.txt:1
written_2/travel_guides/berlitz2/CanaryIslands-WhereToGo.txt:4
written_2/travel_guides/berlitz2/Cancun-History.txt:3
written_2/travel_guides/berlitz2/Cancun-WhatToDo.txt:3
written_2/travel_guides/berlitz2/Cancun-WhereToGo.txt:9
written_2/travel_guides/berlitz2/China-History.txt:3
written_2/travel_guides/berlitz2/China-WhatToDo.txt:3
written_2/travel_guides/berlitz2/China-WhereToGo.txt:27
written_2/travel_guides/berlitz2/Costa-History.txt:2
written_2/travel_guides/berlitz2/Costa-WhatToDo.txt:3
written_2/travel_guides/berlitz2/Costa-WhereToGo.txt:10
written_2/travel_guides/berlitz2/CostaBlanca-History.txt:3
written_2/travel_guides/berlitz2/CostaBlanca-WhatToDo.txt:3
written_2/travel_guides/berlitz2/Crete-History.txt:3
written_2/travel_guides/berlitz2/Crete-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Crete-WhereToGo.txt:15
written_2/travel_guides/berlitz2/CstaBlanca-WhereToGo.txt:5
written_2/travel_guides/berlitz2/Cuba-History.txt:3
written_2/travel_guides/berlitz2/Cuba-WhatToDo.txt:1
written_2/travel_guides/berlitz2/Cuba-WhereToGo.txt:13
written_2/travel_guides/berlitz2/Nepal-History.txt:5
written_2/travel_guides/berlitz2/Nepal-WhatToDo.txt:6
written_2/travel_guides/berlitz2/Nepal-WhereToGo.txt:4
written_2/travel_guides/berlitz2/NewOrleans-History.txt:1
written_2/travel_guides/berlitz2/Paris-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Paris-WhereToGo.txt:6
written_2/travel_guides/berlitz2/Poland-History.txt:0
written_2/travel_guides/berlitz2/Poland-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Portugal-History.txt:0
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Portugal-WhereToGo.txt:11
written_2/travel_guides/berlitz2/PuertoRico-History.txt:2
written_2/travel_guides/berlitz2/PuertoRico-WhatToDo.txt:0
written_2/travel_guides/berlitz2/PuertoRico-WhereToGo.txt:9
written_2/travel_guides/berlitz2/Vallarta-History.txt:3
written_2/travel_guides/berlitz2/Vallarta-WhatToDo.txt:4
written_2/travel_guides/berlitz2/Vallarta-WhereToGo.txt:6
```
This shows how many times "fact" was in a line within each of the .txt files in the written_2/travel_guides/berlitz/ directory. 
