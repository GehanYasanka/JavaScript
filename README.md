what is javascript?
මුලින්ම කිව්වොත් javascript කියන්නේ High-level interpreted programming language එකක්,
මේකෙ  High-level  කියනේ උපුටා ගැනීම් ගොඩක් එක්ක සම්බන්ද වෙච්ච language එකක් ඒවගේම interpreted කියන එකෙන් අපි හදුන්වන්නේ මේ language එකට කිසිම අවස්ථාවක අවශ්‍ය වෙන්නේ නෑ compiler එකක් මේ program එක RUN කරන්න කලින්,
මේක High-level language එකක් නිස මේකට memory management පාවිච්චි වෙන්නේ නෑ

අයි අපි javascript ඉගෙන ගන්නේ?
javascript කියන්නේ browser එකේ language එකක් අපිට client side programming තමයි ගොඩක් වෙලාවට අපිට JavaScript වලින් කරන්න පුළුවන් වෙන්නේ.

JavaScript ගැන මුලින්ම කතා කරනකොට මුලිම අපි දැනගන්න ඕන දෙයක් තමයි variable කියන එක අපි දැන් බලමු variable කියන්න මොකද්ද කියල
JavaScript වලදී variable ගැන කතා කරද්දී ප්‍රදාන වශයෙන් variable 3 තියෙනවා

    1.var

    2.let

    3.const

1. var ගැන කථා කරද්දී JavaScript ආරම්බයේදී තම var කියන variable එක පාවිච්චි වෙන්නේ නමුත් කාලයත් එක්ක var කියන variable එක JavaScript වලින් බාවිතයෙන් ඉවත් වෙනවා එකට හේතුව තමයි var කියන එක globally එකක් ඊක්ට උධහරණය විදියට ගත්තොත් if statement එකක් ඇතුලේ var statement එකක් නම් කරලා if statement  එකෙන් එළියේ ඒ var නම් කලොත් එතන ප්‍රශ්නයක් හට ගන්නවා ඒ කියන්නේ globally තම හැමතිස්සෙම var කියන data type එක තියෙන්නේ 

2.let ගැන බැලුවොත් උදාහරණ එක්ක බලන එක තමයි වඩාත් හොද

    1. let age = 15
    2.
    3.
    4.console.log(age);
    
හරි අපි දැන් මේ 1 line එකේ තියෙන විදියට let use කරලා variable එකක් හදාගෙන එක 4 line console එකේ පෙන්නල තියෙනවා
හරි අපි දැන් බලමු age කියන variable එකටම පස්සේ තව value එකක් දල

    1. let age = 15;
    2.
    3. age = 17;
    4.console.log(age);
    
3 line මොකද වෙන්නේ කියල එතකොට කිසිම අව්ලක් නැතුව එක පස්සේ දාපු value එක console එකේ පෙන්නල තියෙනවා
    
හරි අපි දැන් මේක මේ විදියටම තියෙද්දී let කියන data type එක const වෙනස් කරොත් මේ විදියට

    1. const age = 15;
    2.
    3. age = 17;
    4.console.log(age);
    
අපිට error එකක් බලාගන්න පුළුවන් අපි බලමු ඒ මොකද කියල

ඇත්තටම නියතයක් සදහා බාවිතා කරන data type එකක් තමයි const කියන්නේ ඉතින් const කියන data type එක ඔය variable එකකට බාවිතා කරනවා නම් ඔයාට බාවිතා කරන්න පුළුවන් මුලින් දීපු value එක විතයි තව දෙයක් තමයි const කියන data type  එකට variable එකක් initialization
කරලා විතරක් බෑ එකට value  එකක් එවලේම assign කරන්නම ඕනේ.

හරි අපි කතා කරමු let සහ const කියන data type මොන අවස්ථාවලදී ද බාවිතා වෙන්නේ කියල

මුලින්ම කියන්න ඕන වෙනත් වෙන variable සඳහා let ගෙන් data type එකක් වෙනස් නොවන variable සදහා const කියන Data Type එකක් භාවිතා වෙනවා

Const කියන Data Type එක ගත්තොත් අපිට errors ගොඩක් අඩු කරගන්න පුළුවන් වෙනවා මොකද variable එකට දෙන value එක Const කියන data type එක නිසා අපිට පස්සේ වෙනස් කරගන්න බැරිවෙනවා බැරි වෙනවා ඒ නිසා errors ගොඩක් අඩු කරගන්න පුළුවන් වෙනව ඒ වගේම අපේ code එකට Security එක වැඩි කර ගන්නත් පුලුවන් මේ Const කියන Data Type එක නිසා

මුලින්ම ප්‍රශ්නයක් එන්න පුලුවන් අපි value එකක් reassign කරනකොට const කියන Data Type එක භාවිතා කරන්න බෑ කියන එක හැබැයි අපි JavaScript තවදුරටත් ඉගෙන ගෙන යනකොට කෙලින්ම variable එකක් reassign කරන්නේ නෑ බොහෝ අවස්ථාවලදී අපි ඒ සඳහා arrays create කරනවා object create කරනවා අන්න ඒ වගේ තමයි අපි සාමාන්‍යයෙන් variable value එකක් වෙනස් කරන්න අන්න එතකොට ඕගොල්ලන්ට බලාගන්න පුළුවන් const කියන Data Type එක වෙනස් වෙන්න බැරි variable සඳහාත් භාවිතා කරන්න පුළුවන් කියලා

හරි අපි දැන් බලමු variable වලට values assign කරන්නේ කොහොමද කියල 

variable වලට values assign කරනකොට data type තියෙනවා ඒවා ප්‍රදානවශයෙන් කොටස් දෙකකට බෙදෙනවා

1. primitive data type
2. object data type

primitive data type කියන්නේ directly ඒ data එකට අදාල value එක memory එක යම්කිසි කොටසක් අත්කර ගන්නවා
ඒ සදහා බවිතවෙන ප්‍රධාන data types කිහිපයක් තියෙනව string, number, boolean, null, unified, symbol කියල තියෙනවා  ඔක්කොම ගැන කියන්න යන්නේ නෑ උදහරණ විදියට code එක දැන්නම්

    1. const name = "Gehan";
    2. const age = 12;
    3. const rating = 8.9
    4. const isCool = false;
    5. const f = null;
    6. const t = undefined;
    7.
    8. console.log(typeof name);
    
හරි අපි  දැන් බලමු variable එකකට value එකක් assing කරට පස්සේ concatenation කරන්නේ කොහොමද කියල concatenation කියන්න අපි value දෙකක් එකට එකතු කරන්නේ කොහොමද කියල
    
    1. const name = "Gehan";
    2. const age = 22;
    3.
    4.console.log('My name is '+name +' and I am ' +age);
    
 හරි අපි දැන් බලමු 1,2 line වල තියෙන value එකතු කරන්නේ කොහොමද කියල 
 එක කරන්නේ මේ විදියට 4 line එකේ තියෙන විදියට curly brackets & space හරියටම තියෙන්න ඕනේ නැත්තන් වැඩ කරන්නේ නෑ

හරි අපි දැන් අපි බලමු string properties හදුනා ගන්නේ කොහොමද කියල
එක මම උදාහරණ එක්කම පෙන්නන්නම්

    1. const name = "Gehan Yasanak";
    2. 
    3.
    4. console.log(lenght);
    5. console.log(name.toUppercase());
    6. console.log(name.toLowercase());

මේකෙදි මම string variable එකක් ගත්ත 1 line

මේකේ 4 line එකේ තියෙන්නේ අපි දාපු string value එකේ length එක බලාගන්න පුළුවන් ඒ කියන්නේ characters කියාද කියල
මේකේ 5 line එකේ තියෙන්නේ අපි දාපු string value එකේ ඔක්කොම letters capital කරගන්න පුළුවන්
මේකේ 6 line එකේ තියෙන්නේ අපි දාපු string value එකේ ඔක්කොම letters simple කරගන්න පුළුවන්

හරි අපි දැන් අපි බලමු substring කඩන්නේ කොහොමද කියා සහ තව method එකතු කරන විදිය

    1. const name = "Gehan Yasanak";
    2. 
    3. console.log(name.substring(0,4));

අපිට ඕන උනොත් සම්පුන් string එකෙන් substring එකක් කඩලා ගන්න මේකෙදි අපිට කීවෙනි character එකේ ඉදල කීවෙනි character එකටද කියල දන්න ඕනේ
අපිට මේ 3 line එකේ තියෙන method එක බාවිතා කරන්න පුළුවන්,

    1. const name = "Gehan Yasanak";
    2. 
    3. console.log(name.substring(0,4).toUppercase());

ඒ වගේමයි අපිට මේ method එකට තව method එකක් එකතු කරන්නත් පුළුවන් මේ 3 line එකේ විදියට
එතකොට එන්නේ අපේ range එකක් දල ගත්ත substring එක capital කරන්න පුළුවන්

දැන් අපි බලමු අපි ගත්ත string එකේ character ටික වෙන් වේනම් array එකක් විදියට වෙන් කරන්නේ කොහොමද කියල
එකත් අපි උදාහරණ එක්කම බලමු

    1. const name = "Gehan Yasanak";
    2. 
    3. console.log(name.split(''));
    
3 line එකේ තියෙන විදියට character එකෙන් character එකට වෙන කරන්න බලාපොරොත්තු වෙනවා නම් මේකේ තියෙන විදියට name .split(' '));
මේ වගේ curly brackets දෙකක් ඇතුලේ space එකක් අනිවාර්යයි

දැන් අපි බලමු array එකක් විදියට තියෙන එකක් split කරන්නේ කියල

    1. const name = "namal, kamal, saman, nimal, piyal";
    2. 
    3. console.log(name.split(', '));

මේකෙදි අපේ මේ 1 line එකේ තියෙන value array එකක් විදියට හදාගන්න ඕනේ එකට පොඩි ක්‍රමවේදයක් තියෙනවා ඒ තම comma එකයි
ඊට පස්සේ space එකයි අනිවාර්යයි 

දැන් අපි බලමු මේවා වචන විදියට split කරගන්නේ කියල

3 line එකේ තියෙන විදියට  name .split(', ')); මේකෙදි අපි split කරන්න යන්නේ comma එකයි ඊට පස්සේ space එකෙනුයි කලින් කිව්ව වගේ
දැන් අපිට output එක array එකක් වියට බල ගන්න පුළුවන්
