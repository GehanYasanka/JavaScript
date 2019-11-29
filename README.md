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
