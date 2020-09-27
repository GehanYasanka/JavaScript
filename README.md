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
    
තව පොඩි විශේෂ කාරණයක් කියන්න ඕනේ and, or, not  operator ගැන
 1. && - AND (T && T = T, T && F = F)
 2. || - OR (T || F = T, F || F = F)
 3. ! - NOT (!T = F, !F = T)

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
2. Non primitive data type

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

හරි දැන් අපි බලමු arrays, objects, array objects, introduction to JSON කියන්නේ මොකද්ද කියල.

අපි මුලින්ම බලමු array එකක් කියන්නේ මොකද්ද කියල?
array එකක් කියල අපි හදුන් වන්නේ values කිහිපයක් holde කරන veriable එකක් ,සාමාන්‍ය veriable වල එක values එකක් තමයි තියාගන්න පුළුවන් එත් array එකක veriable කිහිපයක් holde කරන කරලා තියාගන්න

මුලුන් array එකක් define කරලා පෙන්නන්නම්

    1.const fruits = ['apple','orange','pears',15,false];
    2.console.log(fruits);

මේ තමයි සරලවම අපි array එකක් define  කරගන්නේ 

අපිට array එකක් ගත්තහම එක ඇතුලේ අන්තර්ගත කරන්න පුළුවන් ඕනෑම data type එකක් උදාහරණයක් විදියට ගත්තොත් code එකේ තියෙන විදියට string, boolean, number මේවගේ ඕනෙම data type එකක් අන්තර්ගත කරන්න පුළුවන්

තවදෙයක් තමයි නාමකරණයක් javascript වලදී අවශ්‍ය වෙන්නේ නෑ,උදාහරණයක් විදියට ගත්තොත් code එකේ තියන විදියට වෙරිඅබ්ලේ එක මොන data type එකද කියල මුලින් හදුන්වන්න ඕන වෙන්නේ නැ javascript වලදී එක automatically හදුනාගන්නව 

// const name : String

දැන් බලමු කොහොමද array එකක තියෙන element access කරන්නේ කියල,අපිට පුළුවන් array එකක තියෙන ඕනෑම element එකක් access කරන්න මේ code එකේ තියෙන විදියට සහ අපි බලමු element එකක් add කරන්න

    1.const fruits = ['apple','orange','pears',15,false];

    2.console.log(fruits[1]);

    3.fruits[6] = 'grapes';

    4.console.log(fruits);

මේකේ 2 line එකේ කියල තියෙන්නේ fruits කියන array එකේ 2 වෙනි element එක access කර සහ මේ 3 line එකේ කියල තියෙන්නේ 6 වෙනි element එකක් විදියට "grapes" කියල අලුත් value එකක් add කරන විදිය

මං මුලින්ම කියල ඇති වෙනස් වෙන variable වලට අපි බාවිතා කරන්නේ let කියන data type එක නමුත් මං කියල ඇති const කියන data type එක බාවිතා කරලත් අපිට වෙනස් කරන්න පුළුවන් values අපි පාවිච්චි කරන්නේ array එකක් හරි objects එකක් හරි පාවිච්චි කරල

එකට හොදම උදාහරණයක් තමයි අපි කලින් පෙන්නුවේ එකේදී අපි array එකකට values එකතු කරලා පෙන්නුවා(2 line (උඩ code එක)) ඒ කියන්න ඇත්තටම අපි කරලා තියෙන්නේ const කියන data type එකේ values වෙනස් කරලා ඇත්තටම අපිට කරන්න බැරි මේ array එක reassign කරන්න බැරි එක තමයි එක code එකකින් පෙන්නුවොත්

    1.const fruits = ['apple','orange','pears',15,false];

    2.console.log(fruits[1]);

    3.fruits[6] = 'grapes';

    4.console.log(fruits);

    6.fruits = [];

මේකෙදි මං මේ fruits කියන array එක null array (6 line) එකක් කරන්න try කර ඇත්තටම එහෙම කරන්න බෑ එක error එකක්,
array එකට values කතුකරන්න අයින් කරන්න ඒ හැමදේම පුළුවන් ඒත්  array එක reassign කරන්න බැ. ඒ කියන්නේ fruits උඩ දීල තියෙන array එක වෙනස් කරන්න හැකියාවක් නැ 

අපිට ලොකු array element හනක් තියෙන වෙලවකදී අපිට බැහැ ඒ element ගණන් කර කර ඉන්න ඒනිස අපිට ඔන නම් ඒ array එකේ අගට එහෙම නැත්තන් මුලට values එකතු කරන්න සහ අයින් කරන්න අපිට පුලුවන මේ keywords බාවිතා කරලා අගට සහ මුලට values එකතු කරගන්න, අයින් කරන්න

    1.const fruits = ['apple','orange','pears',15,false];
 
    2.fruits.push('mango');

    3.fruits.unshift('banana');

    4.fruits.pop();

    5.console.log(fruits);

මේ 2 line එකේ තියෙන්නේ අගට values add කරලා තියෙනවා, සහ මේ 3 line එකේ තියෙන්නේ  මුලට values add කරලා තියෙනවා. තවත් දෙයක් පුළුවන් අපිට මේ 4 line එකේ තියෙන්නේ array එකේ අවසානයට තියෙන element එක අයින් කරන්න. 

අපිට යනම් කිසි array එකක් නිවැරදි array එක්කද කියල බලාගන්න මේ 1 line එකේ තියෙන keyword එක use කරන්න පුළුවන් මේක cheeking එකක් මේකෙදි අනිවාර්යයෙන්ම boolean output එකක් ඒ කියන්නේ true or false කියල තමයි එන්නේ මේකේ තියෙන විදියට isArray කියල වරහන් ඇතුලේ array name එක දෙන්න පුලුවන්.
තව අපිට පුළුවන් යම්කිසි array එකක array index එක ලබාගන්න එකටමේ 2 line එකේ තියෙන keyword එක බාවිතා කරන්න පුළුවන් මේකෙදි මුලින්ම array නම පස්සේ වරහන් ඇතුලේ අපිට අවෂ්‍ය element එකේ name එක ගන්න පුළුවන්.

    1.console.log(Array.isArray(fruits));
    2.console.log(fruits.indexOf('banana'));
   
හරි දැන් අපි array ගැන කතා කරලා ඉවරයි දැන් අපි බලමු object එකක් කියන්නේ මොකද්ද කියල, සහ object එකක් හදන්නේ කොහොමද කියල.
මුලින්ම අපි object එකක් හදා ගමු මුලිම අපි objectඑකක් හදන්න const කියන variable type එකෙන් තමි හදන්න ඕනේ මේ 1 line එකේ තියෙන විදියට අපි object එකට name එකක් දෙන්න ඕනේ පස්සේ object එක හදන්න ඕනේ මේ 2-11 line එකේ තියෙනවා වගේ සාගල වරහන් ඇතුලේ.
පස්සේ මේ 3 line  එකේ තියෙනවා වෙගේ object එකේ තියෙනේ element වලට colon එකකින් තමයි වෙන්කරලා එයට අදාල variable ටික දෙන්නේ මේ 4 line එකේ තියෙනවා වගේ මේ දෙන හැම variable එකක් ම අපිට දෙන්න වෙන්නේ single quotation එකක් ඇතුලේ තමයි.
තවදෙයක් තමයි අපිට මේ object ඇතුලෙත් array හදාගන්න පුළුවන් මේ 6 line එකේ වගේ.
තව අපිට පුළුවන් අපිට මේ object ඇතුලේ තව object හදන්න පුළුවන් මේ 7-10 line එකේ වගේ ඒවාට අපි විශේෂ නමක් කියනවා embedded object කියල.

    1. const person = 
    2. {
    3.  firstName : 'Gehan',
    4.  LastName : 'Yasanka',
    5.  Age : '16',
    6.  Hobbies : ['Music,Dance'],
    7.  Addres :
    8.			{ street : 'Sampath Uyana',
    9.  		  city : 'Matara',
    10. 		}
    11. }

හරි දැන් අපි බලමු මේ හදාගත්ත object එක console.log එකක් හරහා පෙන්නන්න පුළුවන් ක්‍රම.

දැන් අපි බලමු මේ අපි හදාගත්තු object එකේ ඇතුලේ තියෙන ඔක්කොම data බලන්නේ කොහොමද කියල එකට අපි මේ 1 line එකේ තියෙන මේ command එක use කරනවා.

    1.  console.log(person);

අපිට අවශ්‍ය නම් පුළුවන් මේ තැනට alert එකක් දීල බලන්න 2 line එත් එය මේ අවස්ථවට සාර්ථක ක්‍රමයක් නොවේ.

    2.  altre(person);
    
අපිට පුළුවන් මේ object එක ඇතුලේ තියෙන element වලින් තමන්ට අවශ්‍ය element විතරක් බාවිතා කරන්න මේ 3 line එකේ වගේ.

    3. console.log(person.firstName,person.LastName);
    
ඒවගේම අපිට පුළුවන් මේ object එක ඇතුලේ තියෙන array එකත් access කරන්න මේ 4 line එකේ වගේ.
    
    4. console.log(person.Hobbies[1]);

තවදෙයක් තමයි object එක ඇතුලේ තියෙන තවත් object එකක් (embedded object) access කරනවිදියත් අපිට මේ 5 line එකෙන් බලන්න පුළුවන්

    5. console.log(person.Addres.city);
    
තව අපිට මෙතැනදී පාවිච්චි කරන්න පුළුවන් වෙනවා D structure කියන දේ
මේක ගැන පොඩි හැදින් වීමක් කරොත් මේ object එක ඇතුලේ තියෙන මේ array එක ඇතුලේ තියෙන element එලියට ගන්න ඒවා අපිට එලියට ගත්තම අපිට පුළුවන් directly පාවිච්චි කරන්න.

    6.	const{firstName,LastName} = person;
    
මේ 6 line එකේ තියෙනවා වගේ මේකෙදි අපිට කලින් වගේ ඕන වෙන්නේ නෑ object එක ඇතුලට ගිහින් variable access කරන්න අපි මේ 7 line එකේ හදුන්වල තියෙන නිසා අපිට directly access කරන්න පුළුවන්

    7.	console.log(firstName);
    
එත් එක්කම අපිට අවශ්‍යයි නම් පුළුවන් කලින් 8 line එකටම අපිට මේ වගේ embedded object එකක් උනත් එකතු කරන්න පුළුවන්

    8.	const{firstName,LastName,Addres.{city}} = person; (6 line එකම අලුතින් edit කර ඇත)

ඊට පස්සේ අපිට මේකේ කෙලින්ම අපිට city කියන variable එක access කරන්න පුළුවන් line

    9.	console.log(city);
    
තව අපිට පුළුවන් මේ object එකට අලුතින් element එකතු කරන්න මේ 10 line එකේ වගේ    
    
   10.  person.email = 'gehan@gmail.com';
    
දැන් අපිට මේකේ output එක අරන් බැලුවොත් අලුතින් email කියන attributes එක එකතුවෙලා තියෙනවා 11 line    
    
   11.	console.log(person);    
    
අපි දැන් බලමු array object එකක element access කරන්නේ කියල මේ array object ඒකේ ඇත්තටම තියෙන්නේ array එකක් තමයි තියෙන්නේ ඒ array එක ඇතුලේ object කීපයක් දකින්න පුළුවන් එතකොට array එකේ element විදියට තියෙන්නේ object
මේ 1-17 line එකේ තියෙන්න විදියට todos කියන array element එක ඇතුලේ තමයි objects 3 හදල තියෙන්නේ 

    1.	const todos = [
	
    2.	{
    3.		id:1,
    4.		text:'take out trash',
    5.		isCompleted:false
    6.	},
    7.	{
    8.		id:2,
    9.		text:'meeting with boss',
    10.		isCompleted:false
    11.	},
    12.	{
    13.		id:3,
    14.		text:'raining hear',
    15.		isCompleted:false
    16.	}
    17. ]

දැන් අපිට මේ ඔක්කොගෙම normal output එක බලන්න පුළුවන් මේ 18 line එකෙන් 

    18.	console.log(todos);

හරි දැන් අපි බලමු ඒ array ඇතුලේ තියෙන object access කරන්නේ කොහොමද කියල ඇත්තටම මෙතන මුලින්ම තියෙන්නේ todos කියන array එකක් 

අපිට පළවිනි array element එක එහෙම නැත්තන් පලවෙනි object එකේ text එකට අදාල output එක ගන්න නම් මන් මේ code එක ගහන්න ඕනේ line අපි මේකෙදි 0 වෙනේ array එක access කරලා එකේ ඇතුලේ තියෙන text වල output එක ගන්න එක තමයි මේ කරලා තියෙන්නේ

    19. console.log(todos[0].text);

JSON කියන්නේ මොකද්ද කියල දැන් අපි බලමු JSON කියන්නෙත් data format එකක් මේ JSON කියන data format එක stack development වලදී ඒ වගේම server එකකට data send කරනවා නම් data send කරන format එක JSON format එක තමයි
ඇත්තටම මේ JSON කියන file format එක object එකකට හමාතින්ම අක්රුතියෙනුත් සමානයි object වල key word වල single quotation දානවා වගේ JSON වල key word වල අපි දන්නේ double quotation ඒවගේ පොඩි පොඩි වෙනස්කම් ටිකක් තියෙනවා JSON වල අපි කිසිම අවස්ථාවක single quotation බාවිතා කරන්නේ නැ.

දැන් අපි බලමු අපි මේ array object එක JSON වලට convert කරගන්න.

අපිට කරන්න තියෙන්නේ මේ keyWord එක බාවිතා කරන්න අපි මුලින්ම මේකේ variable එකක් create කරන්න වෙනවා මේ 1 line එකේ වගේ todojson කියන නමින් අපි මේ convert කරගත්තේ කලින් අපි හැදුව todos කියන array object එක (1-17 lines) වල තියෙන.

    1.	const todojson = JSON.stringify(todos);

මේ 1 line එකේ JSON.stringify කියන keyword එකෙන් අපේ array එක string format එකක් බවට පත් වෙනවා මේ වරහන් ඇතුලේ දීල තියෙන්නේ අපි කලින් හද ගත්ත array එක. ඒක සමනකරලා තියෙන්නේ අපිට හැදෙන්න ඕනේ JSON file එකේ name එකට todojson කියන

අපි දැන් බලමු මේක කොහොමද අපිට බලන්න පුළුවන් කියල මේ 2 line එකෙන්

    2.	console.log(todojson);

අපිට දැන් මේක JSON format එකෙන් convert වෙලා තියෙනවා බලාගන්න පුළුවන්.

හරි දැන් අපි කතා කරන්න යන්න loop ගැන ප්‍රදාන වශයෙන් loop වර්ග දෙකකට බෙදෙනවා එකක් for loop  අනෙක while loop
මම මේ දෙක ගැන වැඩිය කතා කරන්නේ නෑ උදාහරණ දෙකකින්ම පෙන්නම්.
	1.for loop
		for(i=1;i<10;i++)
		 {
		  console.log('print': '+i');
		 }
		 
	2.while loop
		let k = 0;
		while (k<10)
		{
		console.log(k);
		k++;
		}
		 
හරි දැන් අපි බලමු කලින් කතා කරලා තියෙන array element එකේ objects for loop එකක් ආදරයෙන් එලියටගන්නෙම් කියල
එකෙට මේ යටින් තියෙන උදාහරණෙ විදියට length කියන keyword එක බාවිතා කරන්න ඕනේ
පස්සේ මේ 1 line එකේ තියෙන විදියට අපිට පෙන්න ඕනේ object එක සදහන් කරන්න ඕනේ

	1.for (let i = 0; i<todos.length;i++)
	2.	{
	3.	console.log(todos[1].text);
	4.	}

හරි දැන් අපි බලමු structures types for loop ලියන්නේ කොහොමද කියාල එක ටිකක් විශේෂ විදියක් මේ යට තියෙන චොදේ එකේ විදියට.

	1.for (let todo of todos)
	2.	{
	3.	console.log(todo);
	4.	}
	
මේකෙන් වෙලා තියෙනේ todo කියන variable එකට todos ඇතුලේ තියෙන ඔක්කොම map වෙලා එහෙම නැත්තන් copy වෙලා වගේ දෙයක් 
මේකේ output එක සම්පුර්නයෙනම අපිට බලාගන්න පුළුවන් වෙනවා

හරි අපි දැන් තව උදාහරණයක් අරන් බලමු අපිට ඕනේ element එක විතරක් එලියට ගන්න නම් උදාහරණයක් විදියට text එක විතරක් ගන්න ඕනේ නම් මේ යට තියෙන code එකේ විදියා දන්නා ඕනේ
මේකේ මේ 3 line එකේ තියෙන විදියට todo.text කියල එකතු වෙලා තියෙනවා

	1.for (let todo of todos)
	2.	{
	3.	console.log(todo.text);
	4.	}
	
හරි දැන් අපි බලමු අලුත් මාතෘකාවක් ඉතිං Higher Order Array Methods ප්‍රදාන වශයෙන් 3ක් තියෙනවා

	1. Foreach - මේකෙදි වෙන්නේ loop වෙන එක විතරයි.
	2. Map - මේකෙදි වෙන්නේ loop එක thru ගිහිල්ල එය නැවත අලුත් array එකක් create කර ගන්නවා.
	3. Filter -  මෙතැනදී අපිට අදාල for loop එකේ loop කරලා අදාල array එක බලල එයට පුළුවන් එකෙන් මොකක් හරි condition එකක් අනුව අලුත් 
    		     array එකක් create කර ගැනීමේ හැකියාව තියෙනවා.


අපි මුලින්ම බලමු 1. ForEach කියන array method එක.

අපි  function එකක් create කරනවා එක ඇත්තටම callback function එකක් එකෙන් අපිට පුළුවන් multiple parameters එකතු කරන්න.

පහල code එකේ තියෙන විදියට 1 line එකේ තියෙන්නේ අපි කලින් නිර්මාණය කරගත්ත variable එක (todo) කියල එකට අපි පලවෙනි parameter එක 
හරි අපි දැන් 2 line  එකේ තියෙන්නේ අපි ගන්නේ todo ගේ text එකක් විදියට loop කරලා todo කියන array එක තුලෙ තියෙන text එක පෙන්නලා තියෙනවා.

	1. todos.forEach(function(todo)) {
	2.    console.log(todo.text); }


