-- This file was generated at discord.gg/syncrypt

local t1 = {}
local v2 = unpack or table.unpack
game:GetService("MarketplaceService")
t1.value1 = game:GetService("UserInputService")
t1.value2 = game:GetService("TweenService")
t1.value3 = game:GetService("HttpService")
t1.value4 = game:GetService("RunService")

local CoreGui = game:GetService("CoreGui")

t1.value5 = game:GetService("Players")
t1.value6 = t1.value5.LocalPlayer
t1.value6:GetMouse()
local colorSequence = ColorSequence.new({
	ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 70, 160)),
	ColorSequenceKeypoint.new(0.5, Color3.fromRGB(0, 0, 0)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 70, 160))
})
local color3 = Color3.fromRGB(0, 0, 0)
local color3_2 = Color3.fromRGB(0, 45, 90)
local color3_3 = Color3.fromRGB(0, 170, 255)
local color3_4 = Color3.fromRGB(255, 255, 255)
local color3_5 = Color3.fromRGB(190, 220, 255)
local t2 = {
	Darker = {
		["Color Hub 1"] = colorSequence,
		["Color Hub 2"] = color3,
		["Color Stroke"] = color3_2,
		["Color Theme"] = color3_3,
		["Color Text"] = color3_4,
		["Color Dark Text"] = color3_5
	}
}
local t3 = {
	Version = "1.1.0"
}
local t4 = {
	UISize = {
		550,
		380
	},
	TabSize = 160,
	Theme = "Darker"
}
t1.value7 = {
	Themes = t2,
	Info = t3,
	Save = t4,
	Settings = {},
	Connection = {},
	Instances = {},
	Elements = {},
	Options = {},
	Flags = {},
	Tabs = {},
	Icons = {
		accessibility = "rbxassetid://10709751939",
		activity = "rbxassetid://10709752035",
		airvent = "rbxassetid://10709752131",
		airplay = "rbxassetid://10709752254",
		alarmcheck = "rbxassetid://10709752405",
		alarmclock = "rbxassetid://10709752630",
		alarmclockoff = "rbxassetid://10709752508",
		alarmminus = "rbxassetid://10709752732",
		alarmplus = "rbxassetid://10709752825",
		album = "rbxassetid://10709752906",
		alertcircle = "rbxassetid://10709752996",
		alertoctagon = "rbxassetid://10709753064",
		alerttriangle = "rbxassetid://10709753149",
		aligncenter = "rbxassetid://10709753570",
		aligncenterhorizontal = "rbxassetid://10709753272",
		aligncentervertical = "rbxassetid://10709753421",
		alignendhorizontal = "rbxassetid://10709753692",
		alignendvertical = "rbxassetid://10709753808",
		alignhorizontaldistributecenter = "rbxassetid://10747779791",
		alignhorizontaldistributeend = "rbxassetid://10747784534",
		alignhorizontaldistributestart = "rbxassetid://10709754118",
		alignhorizontaljustifycenter = "rbxassetid://10709754204",
		alignhorizontaljustifyend = "rbxassetid://10709754317",
		alignhorizontaljustifystart = "rbxassetid://10709754436",
		alignhorizontalspacearound = "rbxassetid://10709754590",
		alignhorizontalspacebetween = "rbxassetid://10709754749",
		alignjustify = "rbxassetid://10709759610",
		alignleft = "rbxassetid://10709759764",
		alignright = "rbxassetid://10709759895",
		alignstarthorizontal = "rbxassetid://10709760051",
		alignstartvertical = "rbxassetid://10709760244",
		alignverticaldistributecenter = "rbxassetid://10709760351",
		alignverticaldistributeend = "rbxassetid://10709760434",
		alignverticaldistributestart = "rbxassetid://10709760612",
		alignverticaljustifycenter = "rbxassetid://10709760814",
		alignverticaljustifyend = "rbxassetid://10709761003",
		alignverticaljustifystart = "rbxassetid://10709761176",
		alignverticalspacearound = "rbxassetid://10709761324",
		alignverticalspacebetween = "rbxassetid://10709761434",
		anchor = "rbxassetid://10709761530",
		angry = "rbxassetid://10709761629",
		annoyed = "rbxassetid://10709761722",
		aperture = "rbxassetid://10709761813",
		apple = "rbxassetid://10709761889",
		archive = "rbxassetid://10709762233",
		archiverestore = "rbxassetid://10709762058",
		armchair = "rbxassetid://10709762327",
		arrowbigdown = "rbxassetid://10747796644",
		arrowbigleft = "rbxassetid://10709762574",
		arrowbigright = "rbxassetid://10709762727",
		arrowbigup = "rbxassetid://10709762879",
		arrowdown = "rbxassetid://10709767827",
		arrowdowncircle = "rbxassetid://10709763034",
		arrowdownleft = "rbxassetid://10709767656",
		arrowdownright = "rbxassetid://10709767750",
		arrowleft = "rbxassetid://10709768114",
		arrowleftcircle = "rbxassetid://10709767936",
		arrowleftright = "rbxassetid://10709768019",
		arrowright = "rbxassetid://10709768347",
		arrowrightcircle = "rbxassetid://10709768226",
		arrowup = "rbxassetid://10709768939",
		arrowupcircle = "rbxassetid://10709768432",
		arrowupdown = "rbxassetid://10709768538",
		arrowupleft = "rbxassetid://10709768661",
		arrowupright = "rbxassetid://10709768787",
		asterisk = "rbxassetid://10709769095",
		atsign = "rbxassetid://10709769286",
		award = "rbxassetid://10709769406",
		axe = "rbxassetid://10709769508",
		axis3d = "rbxassetid://10709769598",
		baby = "rbxassetid://10709769732",
		backpack = "rbxassetid://10709769841",
		baggageclaim = "rbxassetid://10709769935",
		banana = "rbxassetid://10709770005",
		banknote = "rbxassetid://10709770178",
		barchart = "rbxassetid://10709773755",
		barchart2 = "rbxassetid://10709770317",
		barchart3 = "rbxassetid://10709770431",
		barchart4 = "rbxassetid://10709770560",
		barcharthorizontal = "rbxassetid://10709773669",
		barcode = "rbxassetid://10747360675",
		baseline = "rbxassetid://10709773863",
		bath = "rbxassetid://10709773963",
		battery = "rbxassetid://10709774640",
		batterycharging = "rbxassetid://10709774068",
		batteryfull = "rbxassetid://10709774206",
		batterylow = "rbxassetid://10709774370",
		batterymedium = "rbxassetid://10709774513",
		beaker = "rbxassetid://10709774756",
		bed = "rbxassetid://10709775036",
		beddouble = "rbxassetid://10709774864",
		bedsingle = "rbxassetid://10709774968",
		beer = "rbxassetid://10709775167",
		bell = "rbxassetid://10709775704",
		bellminus = "rbxassetid://10709775241",
		belloff = "rbxassetid://10709775320",
		bellplus = "rbxassetid://10709775448",
		bellring = "rbxassetid://10709775560",
		bike = "rbxassetid://10709775894",
		binary = "rbxassetid://10709776050",
		bitcoin = "rbxassetid://10709776126",
		bluetooth = "rbxassetid://10709776655",
		bluetoothconnected = "rbxassetid://10709776240",
		bluetoothoff = "rbxassetid://10709776344",
		bluetoothsearching = "rbxassetid://10709776501",
		bold = "rbxassetid://10747813908",
		bomb = "rbxassetid://10709781460",
		bone = "rbxassetid://10709781605",
		book = "rbxassetid://10709781824",
		bookopen = "rbxassetid://10709781717",
		bookmark = "rbxassetid://10709782154",
		bookmarkminus = "rbxassetid://10709781919",
		bookmarkplus = "rbxassetid://10709782044",
		bot = "rbxassetid://10709782230",
		box = "rbxassetid://10709782497",
		boxselect = "rbxassetid://10709782342",
		boxes = "rbxassetid://10709782582",
		briefcase = "rbxassetid://10709782662",
		brush = "rbxassetid://10709782758",
		bug = "rbxassetid://10709782845",
		building = "rbxassetid://10709783051",
		building2 = "rbxassetid://10709782939",
		bus = "rbxassetid://10709783137",
		cake = "rbxassetid://10709783217",
		calculator = "rbxassetid://10709783311",
		calendar = "rbxassetid://10709789505",
		calendarcheck = "rbxassetid://10709783474",
		calendarcheck2 = "rbxassetid://10709783392",
		calendarclock = "rbxassetid://10709783577",
		calendardays = "rbxassetid://10709783673",
		calendarheart = "rbxassetid://10709783835",
		calendarminus = "rbxassetid://10709783959",
		calendaroff = "rbxassetid://10709788784",
		calendarplus = "rbxassetid://10709788937",
		calendarrange = "rbxassetid://10709789053",
		calendarsearch = "rbxassetid://10709789200",
		calendarx = "rbxassetid://10709789407",
		calendarx2 = "rbxassetid://10709789329",
		camera = "rbxassetid://10709789686",
		cameraoff = "rbxassetid://10747822677",
		car = "rbxassetid://10709789810",
		carrot = "rbxassetid://10709789960",
		cast = "rbxassetid://10709790097",
		charge = "rbxassetid://10709790202",
		check = "rbxassetid://10709790644",
		checkcircle = "rbxassetid://10709790387",
		checkcircle2 = "rbxassetid://10709790298",
		checksquare = "rbxassetid://10709790537",
		chefhat = "rbxassetid://10709790757",
		cherry = "rbxassetid://10709790875",
		chevrondown = "rbxassetid://10709790948",
		chevronfirst = "rbxassetid://10709791015",
		chevronlast = "rbxassetid://10709791130",
		chevronleft = "rbxassetid://10709791281",
		chevronright = "rbxassetid://10709791437",
		chevronup = "rbxassetid://10709791523",
		chevronsdown = "rbxassetid://10709796864",
		chevronsdownup = "rbxassetid://10709791632",
		chevronsleft = "rbxassetid://10709797151",
		chevronsleftright = "rbxassetid://10709797006",
		chevronsright = "rbxassetid://10709797382",
		chevronsrightleft = "rbxassetid://10709797274",
		chevronsup = "rbxassetid://10709797622",
		chevronsupdown = "rbxassetid://10709797508",
		chrome = "rbxassetid://10709797725",
		circle = "rbxassetid://10709798174",
		circledot = "rbxassetid://10709797837",
		circleellipsis = "rbxassetid://10709797985",
		circleslashed = "rbxassetid://10709798100",
		citrus = "rbxassetid://10709798276",
		clapperboard = "rbxassetid://10709798350",
		clipboard = "rbxassetid://10709799288",
		clipboardcheck = "rbxassetid://10709798443",
		clipboardcopy = "rbxassetid://10709798574",
		clipboardedit = "rbxassetid://10709798682",
		clipboardlist = "rbxassetid://10709798792",
		clipboardsignature = "rbxassetid://10709798890",
		clipboardtype = "rbxassetid://10709798999",
		clipboardx = "rbxassetid://10709799124",
		clock = "rbxassetid://10709805144",
		clock1 = "rbxassetid://10709799535",
		clock10 = "rbxassetid://10709799718",
		clock11 = "rbxassetid://10709799818",
		clock12 = "rbxassetid://10709799962",
		clock2 = "rbxassetid://10709803876",
		clock3 = "rbxassetid://10709803989",
		clock4 = "rbxassetid://10709804164",
		clock5 = "rbxassetid://10709804291",
		clock6 = "rbxassetid://10709804435",
		clock7 = "rbxassetid://10709804599",
		clock8 = "rbxassetid://10709804784",
		clock9 = "rbxassetid://10709804996",
		cloud = "rbxassetid://10709806740",
		cloudcog = "rbxassetid://10709805262",
		clouddrizzle = "rbxassetid://10709805371",
		cloudfog = "rbxassetid://10709805477",
		cloudhail = "rbxassetid://10709805596",
		cloudlightning = "rbxassetid://10709805727",
		cloudmoon = "rbxassetid://10709805942",
		cloudmoonrain = "rbxassetid://10709805838",
		cloudoff = "rbxassetid://10709806060",
		cloudrain = "rbxassetid://10709806277",
		cloudrainwind = "rbxassetid://10709806166",
		cloudsnow = "rbxassetid://10709806374",
		cloudsun = "rbxassetid://10709806631",
		cloudsunrain = "rbxassetid://10709806475",
		cloudy = "rbxassetid://10709806859",
		clover = "rbxassetid://10709806995",
		code = "rbxassetid://10709810463",
		code2 = "rbxassetid://10709807111",
		codepen = "rbxassetid://10709810534",
		codesandbox = "rbxassetid://10709810676",
		coffee = "rbxassetid://10709810814",
		cog = "rbxassetid://10709810948",
		coins = "rbxassetid://10709811110",
		columns = "rbxassetid://10709811261",
		command = "rbxassetid://10709811365",
		compass = "rbxassetid://10709811445",
		component = "rbxassetid://10709811595",
		conciergebell = "rbxassetid://10709811706",
		connection = "rbxassetid://10747361219",
		contact = "rbxassetid://10709811834",
		contrast = "rbxassetid://10709811939",
		cookie = "rbxassetid://10709812067",
		copy = "rbxassetid://10709812159",
		copyleft = "rbxassetid://10709812251",
		copyright = "rbxassetid://10709812311",
		cornerdownleft = "rbxassetid://10709812396",
		cornerdownright = "rbxassetid://10709812485",
		cornerleftdown = "rbxassetid://10709812632",
		cornerleftup = "rbxassetid://10709812784",
		cornerrightdown = "rbxassetid://10709812939",
		cornerrightup = "rbxassetid://10709813094",
		cornerupleft = "rbxassetid://10709813185",
		cornerupright = "rbxassetid://10709813281",
		cpu = "rbxassetid://10709813383",
		croissant = "rbxassetid://10709818125",
		crop = "rbxassetid://10709818245",
		cross = "rbxassetid://10709818399",
		crosshair = "rbxassetid://10709818534",
		crown = "rbxassetid://10709818626",
		cupsoda = "rbxassetid://10709818763",
		curlybraces = "rbxassetid://10709818847",
		currency = "rbxassetid://10709818931",
		database = "rbxassetid://10709818996",
		delete = "rbxassetid://10709819059",
		diamond = "rbxassetid://10709819149",
		dice1 = "rbxassetid://10709819266",
		dice2 = "rbxassetid://10709819361",
		dice3 = "rbxassetid://10709819508",
		dice4 = "rbxassetid://10709819670",
		dice5 = "rbxassetid://10709819801",
		dice6 = "rbxassetid://10709819896",
		dices = "rbxassetid://10723343321",
		diff = "rbxassetid://10723343416",
		disc = "rbxassetid://10723343537",
		divide = "rbxassetid://10723343805",
		dividecircle = "rbxassetid://10723343636",
		dividesquare = "rbxassetid://10723343737",
		dollarsign = "rbxassetid://10723343958",
		download = "rbxassetid://10723344270",
		downloadcloud = "rbxassetid://10723344088",
		droplet = "rbxassetid://10723344432",
		droplets = "rbxassetid://10734883356",
		drumstick = "rbxassetid://10723344737",
		edit = "rbxassetid://10734883598",
		edit2 = "rbxassetid://10723344885",
		edit3 = "rbxassetid://10723345088",
		egg = "rbxassetid://10723345518",
		eggfried = "rbxassetid://10723345347",
		electricity = "rbxassetid://10723345749",
		electricityoff = "rbxassetid://10723345643",
		equal = "rbxassetid://10723345990",
		equalnot = "rbxassetid://10723345866",
		eraser = "rbxassetid://10723346158",
		euro = "rbxassetid://10723346372",
		expand = "rbxassetid://10723346553",
		externallink = "rbxassetid://10723346684",
		eye = "rbxassetid://10723346959",
		eyeoff = "rbxassetid://10723346871",
		factory = "rbxassetid://10723347051",
		fan = "rbxassetid://10723354359",
		fastforward = "rbxassetid://10723354521",
		feather = "rbxassetid://10723354671",
		figma = "rbxassetid://10723354801",
		file = "rbxassetid://10723374641",
		filearchive = "rbxassetid://10723354921",
		fileaudio = "rbxassetid://10723355148",
		fileaudio2 = "rbxassetid://10723355026",
		fileaxis3d = "rbxassetid://10723355272",
		filebadge = "rbxassetid://10723355622",
		filebadge2 = "rbxassetid://10723355451",
		filebarchart = "rbxassetid://10723355887",
		filebarchart2 = "rbxassetid://10723355746",
		filebox = "rbxassetid://10723355989",
		filecheck = "rbxassetid://10723356210",
		filecheck2 = "rbxassetid://10723356100",
		fileclock = "rbxassetid://10723356329",
		filecode = "rbxassetid://10723356507",
		filecog = "rbxassetid://10723356830",
		filecog2 = "rbxassetid://10723356676",
		filediff = "rbxassetid://10723357039",
		filedigit = "rbxassetid://10723357151",
		filedown = "rbxassetid://10723357322",
		fileedit = "rbxassetid://10723357495",
		fileheart = "rbxassetid://10723357637",
		fileimage = "rbxassetid://10723357790",
		fileinput = "rbxassetid://10723357933",
		filejson = "rbxassetid://10723364435",
		filejson2 = "rbxassetid://10723364361",
		filekey = "rbxassetid://10723364605",
		filekey2 = "rbxassetid://10723364515",
		filelinechart = "rbxassetid://10723364725",
		filelock = "rbxassetid://10723364957",
		filelock2 = "rbxassetid://10723364861",
		fileminus = "rbxassetid://10723365254",
		fileminus2 = "rbxassetid://10723365086",
		fileoutput = "rbxassetid://10723365457",
		filepiechart = "rbxassetid://10723365598",
		fileplus = "rbxassetid://10723365877",
		fileplus2 = "rbxassetid://10723365766",
		filequestion = "rbxassetid://10723365987",
		filescan = "rbxassetid://10723366167",
		filesearch = "rbxassetid://10723366550",
		filesearch2 = "rbxassetid://1072336340",
		filesignature = "rbxassetid://10723366741",
		filespreadsheet = "rbxassetid://10723366962",
		filesymlink = "rbxassetid://10723367098",
		fileterminal = "rbxassetid://10723367244",
		filetext = "rbxassetid://10723367380",
		filetype = "rbxassetid://10723367606",
		filetype2 = "rbxassetid://10723367509",
		fileup = "rbxassetid://10723367734",
		filevideo = "rbxassetid://10723373884",
		filevideo2 = "rbxassetid://10723367834",
		filevolume = "rbxassetid://10723374172",
		filevolume2 = "rbxassetid://10723374030",
		filewarning = "rbxassetid://10723374276",
		filex = "rbxassetid://10723374544",
		filex2 = "rbxassetid://10723374378",
		files = "rbxassetid://10723374759",
		film = "rbxassetid://10723374981",
		filter = "rbxassetid://10723375128",
		fingerprint = "rbxassetid://10723375250",
		flag = "rbxassetid://10723375890",
    flagoff = "rbxassetid://10723375443",
		flagtriangleleft = "rbxassetid://10723375608",
		flagtriangleright = "rbxassetid://10723375727",
		flame = "rbxassetid://10723376114",
		flashlight = "rbxassetid://10723376471",
		flashlightoff = "rbxassetid://10723376365",
		flaskconical = "rbxassetid://10734883986",
		flaskround = "rbxassetid://10723376614",
		fliphorizontal = "rbxassetid://10723376884",
		fliphorizontal2 = "rbxassetid://10723376745",
		flipvertical = "rbxassetid://10723377138",
		flipvertical2 = "rbxassetid://10723377026",
		flower = "rbxassetid://10747830374",
		flower2 = "rbxassetid://10723377305",
		focus = "rbxassetid://10723377537",
		folder = "rbxassetid://10723387563",
		folderarchive = "rbxassetid://10723384478",
		foldercheck = "rbxassetid://10723384605",
		folderclock = "rbxassetid://10723384731",
		folderclosed = "rbxassetid://10723384893",
		foldercog = "rbxassetid://10723385213",
		foldercog2 = "rbxassetid://10723385036",
		folderdown = "rbxassetid://10723385338",
		folderedit = "rbxassetid://10723385445",
		folderheart = "rbxassetid://10723385545",
		folderinput = "rbxassetid://10723385721",
		folderkey = "rbxassetid://10723385848",
		folderlock = "rbxassetid://10723386005",
		folderminus = "rbxassetid://10723386127",
		folderopen = "rbxassetid://10723386277",
		folderoutput = "rbxassetid://10723386386",
		folderplus = "rbxassetid://10723386531",
		foldersearch = "rbxassetid://10723386787",
		foldersearch2 = "rbxassetid://10723386674",
		foldersymlink = "rbxassetid://10723386930",
		foldertree = "rbxassetid://10723387085",
		folderup = "rbxassetid://10723387265",
		folderx = "rbxassetid://10723387448",
		folders = "rbxassetid://10723387721",
		forminput = "rbxassetid://10723387841",
		forward = "rbxassetid://10723388016",
		frame = "rbxassetid://10723394389",
		framer = "rbxassetid://10723394565",
		frown = "rbxassetid://10723394681",
		fuel = "rbxassetid://10723394846",
		functionsquare = "rbxassetid://10723395041",
		gamepad = "rbxassetid://10723395457",
		gamepad2 = "rbxassetid://10723395215",
		gauge = "rbxassetid://10723395708",
		gavel = "rbxassetid://10723395896",
		gem = "rbxassetid://10723396000",
		ghost = "rbxassetid://10723396107",
		gift = "rbxassetid://10723396402",
		giftcard = "rbxassetid://10723396225",
		gitbranch = "rbxassetid://10723396676",
		gitbranchplus = "rbxassetid://10723396542",
		gitcommit = "rbxassetid://10723396812",
		gitcompare = "rbxassetid://10723396954",
		gitfork = "rbxassetid://10723397049",
		gitmerge = "rbxassetid://10723397165",
		gitpullrequest = "rbxassetid://10723397431",
		gitpullrequestclosed = "rbxassetid://10723397268",
		gitpullrequestdraft = "rbxassetid://10734884302",
		glass = "rbxassetid://10723397788",
		glass2 = "rbxassetid://10723397529",
		glasswater = "rbxassetid://10723397678",
		glasses = "rbxassetid://10723397895",
		globe = "rbxassetid://10723404337",
		globe2 = "rbxassetid://10723398002",
		grab = "rbxassetid://10723404472",
		graduationcap = "rbxassetid://10723404691",
		grape = "rbxassetid://10723404822",
		grid = "rbxassetid://10723404936",
		griphorizontal = "rbxassetid://10723405089",
		gripvertical = "rbxassetid://10723405236",
		hammer = "rbxassetid://10723405360",
		hand = "rbxassetid://10723405649",
		handmetal = "rbxassetid://10723405508",
		harddrive = "rbxassetid://10723405749",
		hardhat = "rbxassetid://10723405859",
		hash = "rbxassetid://10723405975",
		haze = "rbxassetid://10723406078",
		headphones = "rbxassetid://10723406165",
		heart = "rbxassetid://10723406885",
		heartcrack = "rbxassetid://10723406299",
		hearthandshake = "rbxassetid://10723406480",
		heartoff = "rbxassetid://10723406662",
		heartpulse = "rbxassetid://10723406795",
		helpcircle = "rbxassetid://10723406988",
		hexagon = "rbxassetid://10723407092",
		highlighter = "rbxassetid://10723407192",
		history = "rbxassetid://10723407335",
		home = "rbxassetid://10723407389",
		hourglass = "rbxassetid://10723407498",
		icecream = "rbxassetid://10723414308",
		image = "rbxassetid://10723415040",
		imageminus = "rbxassetid://10723414487",
		imageoff = "rbxassetid://10723414677",
		imageplus = "rbxassetid://10723414827",
		import = "rbxassetid://10723415205",
		inbox = "rbxassetid://10723415335",
		indent = "rbxassetid://10723415494",
		indianrupee = "rbxassetid://10723415642",
		infinity = "rbxassetid://10723415766",
		info = "rbxassetid://10723415903",
		inspect = "rbxassetid://10723416057",
		italic = "rbxassetid://10723416195",
		japaneseyen = "rbxassetid://10723416363",
		joystick = "rbxassetid://10723416527",
		key = "rbxassetid://10723416652",
		keyboard = "rbxassetid://10723416765",
		lamp = "rbxassetid://10723417513",
		lampceiling = "rbxassetid://10723416922",
		lampdesk = "rbxassetid://10723417016",
		lampfloor = "rbxassetid://10723417131",
		lampwalldown = "rbxassetid://10723417240",
		lampwallup = "rbxassetid://10723417356",
		landmark = "rbxassetid://10723417608",
		languages = "rbxassetid://10723417703",
		laptop = "rbxassetid://10723423881",
		laptop2 = "rbxassetid://10723417797",
		lasso = "rbxassetid://10723424235",
		lassoselect = "rbxassetid://10723424058",
		laugh = "rbxassetid://10723424372",
		layers = "rbxassetid://10723424505",
		layout = "rbxassetid://10723425376",
		layoutdashboard = "rbxassetid://10723424646",
		layoutgrid = "rbxassetid://10723424838",
		layoutlist = "rbxassetid://10723424963",
		layouttemplate = "rbxassetid://10723425187",
		leaf = "rbxassetid://10723425539",
		library = "rbxassetid://10723425615",
		lifebuoy = "rbxassetid://10723425685",
		lightbulb = "rbxassetid://10723425852",
		lightbulboff = "rbxassetid://10723425762",
		linechart = "rbxassetid://10723426393",
		link = "rbxassetid://10723426722",
		link2 = "rbxassetid://10723426595",
		link2off = "rbxassetid://10723426513",
		list = "rbxassetid://10723433811",
		listchecks = "rbxassetid://10734884548",
		listend = "rbxassetid://10723426886",
		listminus = "rbxassetid://10723426986",
		listmusic = "rbxassetid://10723427081",
		listordered = "rbxassetid://10723427199",
		listplus = "rbxassetid://10723427334",
		liststart = "rbxassetid://10723427494",
		listvideo = "rbxassetid://10723427619",
		listx = "rbxassetid://10723433655",
		loader = "rbxassetid://10723434070",
		loader2 = "rbxassetid://10723433935",
		locate = "rbxassetid://10723434557",
		locatefixed = "rbxassetid://10723434236",
		locateoff = "rbxassetid://10723434379",
		lock = "rbxassetid://10723434711",
		login = "rbxassetid://10723434830",
		logout = "rbxassetid://10723434906",
		luggage = "rbxassetid://10723434993",
		magnet = "rbxassetid://10723435069",
		mail = "rbxassetid://10734885430",
		mailcheck = "rbxassetid://10723435182",
		mailminus = "rbxassetid://10723435261",
		mailopen = "rbxassetid://10723435342",
		mailplus = "rbxassetid://10723435443",
		mailquestion = "rbxassetid://10723435515",
		mailsearch = "rbxassetid://10734884739",
		mailwarning = "rbxassetid://10734885015",
		mailx = "rbxassetid://10734885247",
		mails = "rbxassetid://10734885614",
		map = "rbxassetid://10734886202",
		mappin = "rbxassetid://10734886004",
		mappinoff = "rbxassetid://10734885803",
		maximize = "rbxassetid://10734886735",
		maximize2 = "rbxassetid://10734886496",
		medal = "rbxassetid://10734887072",
		megaphone = "rbxassetid://10734887454",
		megaphoneoff = "rbxassetid://10734887311",
		meh = "rbxassetid://10734887603",
		menu = "rbxassetid://10734887784",
		messagecircle = "rbxassetid://10734888000",
		messagesquare = "rbxassetid://10734888228",
		mic = "rbxassetid://10734888864",
		mic2 = "rbxassetid://10734888430",
		micoff = "rbxassetid://10734888646",
		microscope = "rbxassetid://10734889106",
		microwave = "rbxassetid://10734895076",
		milestone = "rbxassetid://10734895310",
		minimize = "rbxassetid://10734895698",
		minimize2 = "rbxassetid://10734895530",
		minus = "rbxassetid://10734896206",
		minuscircle = "rbxassetid://10734895856",
		minussquare = "rbxassetid://10734896029",
		monitor = "rbxassetid://10734896881",
		monitoroff = "rbxassetid://10734896360",
		monitorspeaker = "rbxassetid://10734896512",
		moon = "rbxassetid://10734897102",
		morehorizontal = "rbxassetid://10734897250",
		morevertical = "rbxassetid://10734897387",
		mountain = "rbxassetid://10734897956",
		mountainsnow = "rbxassetid://10734897665",
		mouse = "rbxassetid://10734898592",
		mousepointer = "rbxassetid://10734898476",
		mousepointer2 = "rbxassetid://10734898194",
		mousepointerclick = "rbxassetid://10734898355",
		move = "rbxassetid://10734900011",
		move3d = "rbxassetid://10734898756",
		movediagonal = "rbxassetid://10734899164",
		movediagonal2 = "rbxassetid://10734898934",
		movehorizontal = "rbxassetid://10734899414",
		movevertical = "rbxassetid://10734899821",
		music = "rbxassetid://10734905958",
		music2 = "rbxassetid://10734900215",
		music3 = "rbxassetid://10734905665",
		music4 = "rbxassetid://10734905823",
		navigation = "rbxassetid://10734906744",
		navigation2 = "rbxassetid://10734906332",
		navigation2off = "rbxassetid://10734906144",
		navigationoff = "rbxassetid://10734906580",
		network = "rbxassetid://10734906975",
		newspaper = "rbxassetid://10734907168",
		octagon = "rbxassetid://10734907361",
		option = "rbxassetid://10734907649",
		outdent = "rbxassetid://10734907933",
		package = "rbxassetid://10734909540",
		package2 = "rbxassetid://10734908151",
		packagecheck = "rbxassetid://10734908384",
		packageminus = "rbxassetid://10734908626",
		packageopen = "rbxassetid://10734908793",
		packageplus = "rbxassetid://10734909016",
		packagesearch = "rbxassetid://10734909196",
		packagex = "rbxassetid://10734909375",
		paintbucket = "rbxassetid://10734909847",
		paintbrush = "rbxassetid://10734910187",
		paintbrush2 = "rbxassetid://10734910030",
		palette = "rbxassetid://10734910430",
		palmtree = "rbxassetid://10734910680",
		paperclip = "rbxassetid://10734910927",
		partypopper = "rbxassetid://10734918735",
		pause = "rbxassetid://10734919336",
		pausecircle = "rbxassetid://10735024209",
		pauseoctagon = "rbxassetid://10734919143",
		pentool = "rbxassetid://10734919503",
		pencil = "rbxassetid://10734919691",
		percent = "rbxassetid://10734919919",
		personstanding = "rbxassetid://10734920149",
		phone = "rbxassetid://10734921524",
		phonecall = "rbxassetid://10734920305",
		phoneforwarded = "rbxassetid://10734920508",
		phoneincoming = "rbxassetid://10734920694",
		phonemissed = "rbxassetid://10734920845",
		phoneoff = "rbxassetid://10734921077",
		phoneoutgoing = "rbxassetid://10734921288",
		piechart = "rbxassetid://10734921727",
		piggybank = "rbxassetid://10734921935",
		pin = "rbxassetid://10734922324",
		pinoff = "rbxassetid://10734922180",
		pipette = "rbxassetid://10734922497",
		pizza = "rbxassetid://10734922774",
		plane = "rbxassetid://10734922971",
		play = "rbxassetid://10734923549",
		playcircle = "rbxassetid://10734923214",
		plus = "rbxassetid://10734924532",
		pluscircle = "rbxassetid://10734923868",
		plussquare = "rbxassetid://10734924219",
		podcast = "rbxassetid://10734929553",
		pointer = "rbxassetid://10734929723",
		poundsterling = "rbxassetid://10734929981",
		power = "rbxassetid://10734930466",
		poweroff = "rbxassetid://10734930257",
		printer = "rbxassetid://10734930632",
		puzzle = "rbxassetid://10734930886",
		quote = "rbxassetid://10734931234",
		radio = "rbxassetid://10734931596",
		radioreceiver = "rbxassetid://10734931402",
		rectanglehorizontal = "rbxassetid://10734931777",
		rectanglevertical = "rbxassetid://10734932081",
		recycle = "rbxassetid://10734932295",
		redo = "rbxassetid://10734932822",
		redo2 = "rbxassetid://10734932586",
		refreshccw = "rbxassetid://10734933056",
		refreshcw = "rbxassetid://10734933222",
		refrigerator = "rbxassetid://10734933465",
		regex = "rbxassetid://10734933655",
		["repeat"] = "rbxassetid://10734933966",
		repeat1 = "rbxassetid://10734933826",
		reply = "rbxassetid://10734934252",
		replyall = "rbxassetid://10734934132",
		rewind = "rbxassetid://10734934347",
		rocket = "rbxassetid://10734934585",
		rockingchair = "rbxassetid://10734939942",
		rotate3d = "rbxassetid://10734940107",
		rotateccw = "rbxassetid://10734940376",
		rotatecw = "rbxassetid://10734940654",
		rss = "rbxassetid://10734940825",
		ruler = "rbxassetid://10734941018",
		russianruble = "rbxassetid://10734941199",
		sailboat = "rbxassetid://10734941354",
		save = "rbxassetid://10734941499",
		scale = "rbxassetid://10734941912",
		scale3d = "rbxassetid://10734941739",
		scaling = "rbxassetid://10734942072",
		scan = "rbxassetid://10734942565",
		scanface = "rbxassetid://10734942198",
		scanline = "rbxassetid://10734942351",
		scissors = "rbxassetid://10734942778",
		screenshare = "rbxassetid://10734943193",
		screenshareoff = "rbxassetid://10734942967",
		scroll = "rbxassetid://10734943448",
		search = "rbxassetid://10734943674",
		send = "rbxassetid://10734943902",
		separatorhorizontal = "rbxassetid://10734944115",
		separatorvertical = "rbxassetid://10734944326",
		server = "rbxassetid://10734949856",
		servercog = "rbxassetid://10734944444",
		servercrash = "rbxassetid://10734944554",
		serveroff = "rbxassetid://10734944668",
		settings = "rbxassetid://10734950309",
		settings2 = "rbxassetid://10734950020",
		share = "rbxassetid://10734950813",
		share2 = "rbxassetid://10734950553",
		sheet = "rbxassetid://10734951038",
		shield = "rbxassetid://10734951847",
		shieldalert = "rbxassetid://10734951173",
		shieldcheck = "rbxassetid://10734951367",
		shieldclose = "rbxassetid://10734951535",
		shieldoff = "rbxassetid://10734951684",
		shirt = "rbxassetid://10734952036",
		shoppingbag = "rbxassetid://10734952273",
		shoppingcart = "rbxassetid://10734952479",
		shovel = "rbxassetid://10734952773",
		showerhead = "rbxassetid://10734952942",
		shrink = "rbxassetid://10734953073",
		shrub = "rbxassetid://10734953241",
		shuffle = "rbxassetid://10734953451",
		sidebar = "rbxassetid://10734954301",
		sidebarclose = "rbxassetid://10734953715",
		sidebaropen = "rbxassetid://10734954000",
		sigma = "rbxassetid://10734954538",
		signal = "rbxassetid://10734961133",
		signalhigh = "rbxassetid://10734954807",
		signallow = "rbxassetid://10734955080",
		signalmedium = "rbxassetid://10734955336",
		signalzero = "rbxassetid://10734960878",
		siren = "rbxassetid://10734961284",
		skipback = "rbxassetid://10734961526",
		skipforward = "rbxassetid://10734961809",
		skull = "rbxassetid://10734962068",
		slack = "rbxassetid://10734962339",
		slash = "rbxassetid://10734962600",
		slice = "rbxassetid://10734963024",
		sliders = "rbxassetid://10734963400",
		slidershorizontal = "rbxassetid://10734963191",
		smartphone = "rbxassetid://10734963940",
		smartphonecharging = "rbxassetid://10734963671",
		smile = "rbxassetid://10734964441",
		smileplus = "rbxassetid://10734964188",
		snowflake = "rbxassetid://10734964600",
		sofa = "rbxassetid://10734964852",
		sortasc = "rbxassetid://10734965115",
		sortdesc = "rbxassetid://10734965287",
		speaker = "rbxassetid://10734965419",
		sprout = "rbxassetid://10734965572",
		square = "rbxassetid://10734965702",
		star = "rbxassetid://10734966248",
		starhalf = "rbxassetid://10734965897",
		staroff = "rbxassetid://10734966097",
		stethoscope = "rbxassetid://10734966384",
		sticker = "rbxassetid://10734972234",
		stickynote = "rbxassetid://10734972463",
		stopcircle = "rbxassetid://10734972621",
		stretchhorizontal = "rbxassetid://10734972862",
		stretchvertical = "rbxassetid://10734973130",
		strikethrough = "rbxassetid://10734973290",
		subscript = "rbxassetid://10734973457",
		sun = "rbxassetid://10734974297",
		sundim = "rbxassetid://10734973645",
		sunmedium = "rbxassetid://10734973778",
		sunmoon = "rbxassetid://10734973999",
		sunsnow = "rbxassetid://10734974130",
		sunrise = "rbxassetid://10734974522",
		sunset = "rbxassetid://10734974689",
		superscript = "rbxassetid://10734974850",
		swissfranc = "rbxassetid://10734975024",
		switchcamera = "rbxassetid://10734975214",
		sword = "rbxassetid://10734975486",
		swords = "rbxassetid://10734975692",
		syringe = "rbxassetid://10734975932",
		table = "rbxassetid://10734976230",
		table2 = "rbxassetid://10734976097",
		tablet = "rbxassetid://10734976394",
		tag = "rbxassetid://10734976528",
		tags = "rbxassetid://10734976739",
		target = "rbxassetid://10734977012",
		tent = "rbxassetid://10734981750",
		terminal = "rbxassetid://10734982144",
		terminalsquare = "rbxassetid://10734981995",
    textcursor = "rbxassetid://10734982395",
		textcursorinput = "rbxassetid://10734982297",
		thermometer = "rbxassetid://10734983134",
		thermometersnowflake = "rbxassetid://10734982571",
		thermometersun = "rbxassetid://10734982771",
		thumbsdown = "rbxassetid://10734983359",
		thumbsup = "rbxassetid://10734983629",
		ticket = "rbxassetid://10734983868",
		timer = "rbxassetid://10734984606",
		timeroff = "rbxassetid://10734984138",
		timerreset = "rbxassetid://10734984355",
		toggleleft = "rbxassetid://10734984834",
		toggleright = "rbxassetid://10734985040",
		tornado = "rbxassetid://10734985247",
		toybrick = "rbxassetid://10747361919",
		train = "rbxassetid://10747362105",
		trash = "rbxassetid://10747362393",
		trash2 = "rbxassetid://10747362241",
		treedeciduous = "rbxassetid://10747362534",
		treepine = "rbxassetid://10747362748",
		trees = "rbxassetid://10747363016",
		trendingdown = "rbxassetid://10747363205",
		trendingup = "rbxassetid://10747363465",
		triangle = "rbxassetid://10747363621",
		trophy = "rbxassetid://10747363809",
		truck = "rbxassetid://10747364031",
		tv = "rbxassetid://10747364593",
		tv2 = "rbxassetid://10747364302",
		type = "rbxassetid://10747364761",
		umbrella = "rbxassetid://10747364971",
		underline = "rbxassetid://10747365191",
		undo = "rbxassetid://10747365484",
		undo2 = "rbxassetid://10747365359",
		unlink = "rbxassetid://10747365771",
		unlink2 = "rbxassetid://10747397871",
		unlock = "rbxassetid://10747366027",
		upload = "rbxassetid://10747366434",
		uploadcloud = "rbxassetid://10747366266",
		usb = "rbxassetid://10747366606",
		user = "rbxassetid://10747373176",
		usercheck = "rbxassetid://10747371901",
		usercog = "rbxassetid://10747372167",
		userminus = "rbxassetid://10747372346",
		userplus = "rbxassetid://10747372702",
		userx = "rbxassetid://10747372992",
		users = "rbxassetid://10747373426",
		utensils = "rbxassetid://10747373821",
		utensilscrossed = "rbxassetid://10747373629",
		venetianmask = "rbxassetid://10747374003",
		verified = "rbxassetid://10747374131",
		vibrate = "rbxassetid://10747374489",
		vibrateoff = "rbxassetid://10747374269",
		video = "rbxassetid://10747374938",
		videooff = "rbxassetid://10747374721",
		view = "rbxassetid://10747375132",
		voicemail = "rbxassetid://10747375281",
		volume = "rbxassetid://10747376008",
		volume1 = "rbxassetid://10747375450",
		volume2 = "rbxassetid://10747375679",
		volumex = "rbxassetid://10747375880",
		wallet = "rbxassetid://10747376205",
		wand = "rbxassetid://10747376565",
		wand2 = "rbxassetid://10747376349",
		watch = "rbxassetid://10747376722",
		waves = "rbxassetid://10747376931",
		webcam = "rbxassetid://10747381992",
		wifi = "rbxassetid://10747382504",
		wifioff = "rbxassetid://10747382268",
		wind = "rbxassetid://10747382750",
		wraptext = "rbxassetid://10747383065",
		wrench = "rbxassetid://10747383470",
		x = "rbxassetid://10747384394",
		xcircle = "rbxassetid://10747383819",
		xoctagon = "rbxassetid://10747384037",
		xsquare = "rbxassetid://10747384217",
		zoomin = "rbxassetid://10747384552",
		zoomout = "rbxassetid://10747384679"
	}
}
t1.value8 = workspace.CurrentCamera.ViewportSize
t1.value9 = t1.value8.Y / 450
t1.value10 = t1.value7.Settings
t1.value11 = t1.value7.Flags
t1.value12 = nil
function t1.value13(p1, p2)
    table.insert(t1.value7.Instances, {
		Instance = p1,
		Type = p2
	})

    return p1
end
function t1.value14(p3, p4)
    if p4 then
        for _, v in pairs(p4) do
            v.Parent = p3
        end
    end

    return p3
end
function t1.value12(p5, p6)
    if p6 then
        for k, v in pairs(p6) do
            p5[k] = v
        end
    end

    return p5
end
function t1.value15(...)
    local t5 = { ... }

    if type(t5) ~= "table" then
        return
    end

    local v28 = Instance.new(t5[1])

    if type(t5[2]) == "table" then
        local v29 = t5[2]

        t1.value12(v28, v29)
        t1.value14(v28, t5[3])

        if t5[3] then
            return v28
        end
    elseif typeof(t5[2]) == "Instance" then
        v28.Parent = t5[2]

        local v30 = t5[3]

        t1.value12(v28, v30)
        t1.value14(v28, t5[4])

        if not t5[4] then
        end
    end

    return v28
end
pcall(function(p7)
    local _readfile = readfile

    if _readfile then
        _readfile = isfile and isfile(p7)
    end

    if _readfile then
        local data = t1.value3:JSONDecode(readfile(p7))

        if type(data) == "table" then
            if rawget(data, "UISize") then
                t1.value7.Save.UISize = data.UISize
            end

            if rawget(data, "TabSize") then
                t1.value7.Save.TabSize = data.TabSize
            end

            local v34 = rawget(data, "Theme")

            if v34 then
                v34 = VerifyTheme(data.Theme)
            end

            if v34 then
                t1.value7.Save.Theme = data.Theme
            end
        end
    end
end, "redz library V5.json")
t1.value16 = {}
function t1.value16.InsertCallback(_, p9, p10)
    if type(p10) == "function" then
        table.insert(p9, p10)
    end

    return p10
end
function t1.value16.FireCallback(_, p12, ...)
    for _, v in ipairs(p12) do
        if type(v) == "function" then
            task.spawn(v, ...)
        end
    end
end
function t1.value16.ToggleVisible(_, p14, p15)
    p14.Visible = p15 ~= nil and p15 or not p14.Visible
end
function t1.value16.ToggleParent(_, p17, p18, p19)
    if p18 ~= nil then
        p17.Parent = p18 and p19 or nil

        return
    end

    p17.Parent = p17.Parent == nil and p19 or nil
end
function t1.value16.GetConnectionFunctions(_, p21, p22)
    return {
		Function = p22,
		Connected = true,
		Disconnect = function(p23)
        if p23.Connected then
            table.remove(p21, table.find(p21, p23.Function))
            p23.Connected = false
        end
    end,
		Fire = function(p24, ...)
        if p24.Connected then
            task.spawn(p24.Function, ...)
        end
    end
	}
end
function t1.value16.GetCallback(_, p26, p27)
    local v55 = p26[p27]

    if not v55 then
        v55 = p26.Callback or function()
        end
    end

    local v56 = v55

    if type(v56) == "table" then
        return { function(p28)
            v56[1][v56[2]] = p28
        end }
    end

    return { v56 }
end
local Connection = t1.value7.Connection
t1.value17 = {}
t1.value18 = Connection
function t1.value18.FireConnection(_, p30, ...)
    local v64 = type(p30) == "string" and t1.value17[p30]

    if not v64 then
        v64 = t1.value17[p30.Name]
    end

    for _, v in pairs(v64) do
        task.spawn(v, ...)
    end
end;
(function(p31)
    if type(p31) ~= "table" then
        return
    end

    for _, v in ipairs(p31) do
        local t6 = {}
        local t7 = {}

        t1.value18[v] = t6
        t1.value17[v] = t7
        t6.Name = v

        function t6.Connect(_, p33)
            if type(p33) == "function" then
                table.insert(t7, p33)

                return t1.value16:GetConnectionFunctions(t7, p33)
            end
        end
        function t6.Once(_, p35)
            if type(p35) == "function" then
                return (t1.value16:GetConnectionFunctions(t7, function(...)
                    task.spawn(p35, ...);
                    (nil):Disconnect()
                end))
            end
        end
    end
end)({
	"FlagsChanged",
	"ThemeChanged",
	"FileSaved",
	"ThemeChanging",
	"OptionAdded",
	"DesignApplied"
})
function t1.value19(p36)
    return type(p36) == "string" and t1.value11[p36]
end
function t1.value20(p37, p38)
    local v70 = p37

    if p37 then
        v70 = p38 ~= t1.value11[p37]

        if not v70 then
            v70 = type(p38) == "table"
        end
    end

    if v70 then
        t1.value11[p37] = p38
        t1.value18:FireConnection("FlagsChanged", p37, p38)
    end
end
t1.value21 = nil
t1.value18.FlagsChanged:Connect(function(_, _)
    local ScriptFile = t1.value10.ScriptFile
    local v75 = not t1.value21

    if v75 then
        v75 = ScriptFile and writefile
    end

    if v75 then
        task.wait(0.1)

        local ok, result = pcall(function()
            return t1.value3:JSONEncode(t1.value11)
        end)

        if ok and pcall(writefile, ScriptFile, result) then
            t1.value18:FireConnection("FileSaved", "Script-Flags", ScriptFile, result)
        end
    end
end)
t1.value22 = t1.value15("ScreenGui", CoreGui, {
	Name = "redz Library V5"
}, { t1.value15("UIScale", {
	Scale = t1.value9,
	Name = "Scale"
}) })
t1.value22.ZIndexBehavior = Enum.ZIndexBehavior.Global
local t1value22Name = CoreGui:FindFirstChild(t1.value22.Name)

if t1value22Name and t1value22Name ~= t1.value22 then
    t1value22Name:Destroy()
end
t1.value23 = false
t1.value24 = "rbxassetid://6042053626"
t1.value25 = t1.value15("Folder", t1.value22, {
	Name = "ClickSounds"
})
function t1.value26()
    if not t1.value23 then
        return
    end

    local str = tostring(t1.value24 or "")

    if str == "" then
        return
    end

    if not str:find("rbxassetid://") then
        str = "rbxassetid://" .. str
    end

    local v86 = t1.value15("Sound", t1.value25, {
		SoundId = str,
		Volume = 0.5
	})

    v86:Play()
    game:GetService("Debris"):AddItem(v86, 3)
end
function t1.value27(p41)
    if type(p41) == "function" then
        return p41()
    end

    return p41
end
function t1.value28(p42, p43)
    p42.InputBegan:Connect(function(input)
        local v342 = input.UserInputType == Enum.UserInputType.MouseButton1

        if not v342 then
            v342 = input.UserInputType == Enum.UserInputType.Touch
        end

        if v342 then
            while t1.value1:IsMouseButtonPressed(Enum.UserInputType.MouseButton1) do
                task.wait()
            end
        end

        p43()
    end)
end
function t1.value29(p44)
    local v90 = p44[1] or p44.Instance
    local v91 = p44[2] or p44.Prop
    local v92 = p44[3] or p44.NewVal
    local v93 = p44[4] or (p44.Time or 0.5)
    local v94 = p44[5] or (p44.wait or false)
    local new = TweenInfo.new
    local Quint = Enum.EasingStyle.Quint
    local t8 = {
		[v91] = v92
	}
    local v98 = new(v93, Quint)
    local v99 = t1.value2:Create(v90, v98, t8)

    v99:Play()

    if v94 then
        v99.Completed:Wait()
    end

    return v99
end
local function v15(p45)
    task.spawn(function()
        t1.value12(p45, {
			Active = true,
			AutoButtonColor = false
		})
        local p45Position
        local u344
        local function v345(p46)
            local v611 = p46.Position - nil
            local uDim2 = UDim2.new(p45Position.X.Scale, p45Position.X.Offset + v611.X / t1.value9, p45Position.Y.Scale, p45Position.Y.Offset + v611.Y / t1.value9)

            t1.value29({
				p45,
				"Position",
				uDim2,
				0.35
			})
        end
        p45.MouseButton1Down:Connect(function()
            u344 = true
        end)
        p45.InputBegan:Connect(function(input)
            local v614 = input.UserInputType == Enum.UserInputType.MouseButton1

            if not v614 then
                v614 = input.UserInputType == Enum.UserInputType.Touch
            end

            if v614 then
                p45Position = p45.Position

                local _ = input.Position

                while t1.value1:IsMouseButtonPressed(Enum.UserInputType.MouseButton1) do
                    t1.value4.Heartbeat:Wait()

                    if u344 then
                        v345(input)
                    end
                end
            end
        end)
    end)

    return p45
end
function t1.value30(p47)
    for k, _ in pairs(t1.value7.Themes) do
        if k == p47 then
            return true
        end
    end
end
function t1.value31(p48, p49)
    if writefile then
        local json = t1.value3:JSONEncode(p49)

        writefile(p48, json)
    end
end
t1.value32 = t1.value7.Themes[t1.value7.Save.Theme]

function t1.value33(p50, p51, p52, ...)
    return (t1.value7.Elements[p50](p51, p52, ...))
end
local function v16(p53, p54)
    t1.value7.Elements[p53] = p54
end
v16("Corner", function(p55, p56)
    local value15 = t1.value15

    if not p56 then
        p56 = UDim.new(0, 7)
    end

    return (value15("UICorner", p55, {
		CornerRadius = p56
	}))
end)
v16("Stroke", function(p57, p58, ...)
    local v111, v112 = ...
    local value13 = t1.value13
    local value12 = t1.value12
    local value15 = t1.value15

    if not v111 then
        v111 = t1.value32["Color Stroke"]
    end

    local v116 = v112 or 1

    return (value13(value12(value15("UIStroke", p57, {
		Color = v111,
		Thickness = v116,
		ApplyStrokeMode = "Border"
	}), p58), "Stroke"))
end)
v16("Button", function(p59, p60, ...)
    local t9 = { ... }
    local value13 = t1.value13
    local value12 = t1.value12
    local value15 = t1.value15
    local uDim2 = UDim2.fromScale(1, 1)
    local v124 = t1.value32["Color Hub 2"]
    local v125 = value13(value12(value15("TextButton", p59, {
		Text = "",
		Size = uDim2,
		BackgroundColor3 = v124,
		AutoButtonColor = false
	}), p60), "Frame")

    v125.MouseEnter:Connect(function()
        v125.BackgroundTransparency = 0.4
    end)
    v125.MouseLeave:Connect(function()
        v125.BackgroundTransparency = 0
    end)
    v125.Activated:Connect(t1.value26)

    if t9[1] then
        v125.Activated:Connect(t9[1])
    end

    return v125
end)
v16("Gradient", function(p61, p62, ...)
    return (t1.value13(t1.value12(t1.value15("UIGradient", p61, {
		Color = t1.value32["Color Hub 1"]
	}), p62), "Gradient"))
end)
v16("Shadow", function(p63, p64)
    if not p64 then
        p64 = {}
    end

    local v130 = p64.Spread or 24
    local value15 = t1.value15
    local p64Color = p64.Color

    if not p64Color then
        p64Color = Color3.fromRGB(0, 0, 0)
    end

    local v133 = p64.Transparency or 0.55
    local Slice = Enum.ScaleType.Slice
    local rect = Rect.new(49, 49, 450, 450)
    local uDim2 = UDim2.new(1, v130, 1, v130)
    local uDim2_2 = UDim2.new(0.5, 0, 0.5, p64.YOffset or 3)
    local vector2 = Vector2.new(0.5, 0.5)
    local v139 = p64.ZIndex or 0
    local v140 = value15("ImageLabel", p63, {
		Name = "Shadow",
		BackgroundTransparency = 1,
		Image = "rbxassetid://5028857084",
		ImageColor3 = p64Color,
		ImageTransparency = v133,
		ScaleType = Slice,
		SliceCenter = rect,
		Size = uDim2,
		Position = uDim2_2,
		AnchorPoint = vector2,
		ZIndex = v139
	})

    v140:SetAttribute("IsShadow", true)

    return v140
end)
t1.value34 = {
	Toggle = 10,
	Button = 10,
	Paragraph = 10,
	Dropdown = 14,
	Slider = 10,
	TextBox = 10,
	Section = 14,
	ColorPicker = 10
}
t1.value35 = {
	Toggle = {},
	Button = {},
	Paragraph = {},
	Dropdown = {},
	Slider = {},
	TextBox = {},
	Section = {},
	ColorPicker = {}
}
function t1.value36(p65, p66, p67, p68, p69)
    local v147 = t1.value34[p69] or 10
    local value13 = t1.value13
    local value15 = t1.value15
    local GothamMedium = Enum.Font.GothamMedium
    local v151 = t1.value32["Color Text"]
    local uDim2 = UDim2.new(1, -20)
    local uDim2_3 = UDim2.new(0, 0, 0.5)
    local vector2 = Vector2.new(0, 0.5)
    local v155 = value13(value15("TextLabel", {
		Font = GothamMedium,
		TextColor3 = v151,
		Size = uDim2,
		AutomaticSize = "Y",
		Position = uDim2_3,
		AnchorPoint = vector2,
		BackgroundTransparency = 1,
		TextTruncate = "AtEnd",
		TextSize = v147,
		TextXAlignment = "Left",
		Text = "",
		RichText = true
	}), "Text")
    local value13_2 = t1.value13
    local value15_2 = t1.value15
    local Gotham = Enum.Font.Gotham
    local v159 = t1.value32["Color Dark Text"]
    local uDim2_4 = UDim2.new(1, -20)
    local uDim2_5 = UDim2.new(0, 12, 0, 15)
    local v162 = math.max(6, (math.floor(v147 * 0.8)))
    local v163 = value13_2(value15_2("TextLabel", {
		Font = Gotham,
		TextColor3 = v159,
		Size = uDim2_4,
		AutomaticSize = "Y",
		Position = uDim2_5,
		BackgroundTransparency = 1,
		TextWrapped = true,
		TextSize = v162,
		TextXAlignment = "Left",
		Text = "",
		RichText = true
	}), "DarkText")
    local v164 = t1.value33("Button", p65, {
		Size = UDim2.new(1, 0, 0, 27),
		AutomaticSize = "Y",
		Name = "Option"
	})

    t1.value33("Corner", v164, UDim.new(0, 6))

    local value15_3 = t1.value15
    local uDim2_6 = UDim2.new(0, 10, 0)
    local vector2_2 = Vector2.new(0, 0)
    local t10 = {
		AutomaticSize = "Y",
		BackgroundTransparency = 1,
		Size = p68,
		Position = uDim2_6,
		AnchorPoint = vector2_2
	}
    local value15_4 = t1.value15
    local uDim = UDim.new(0, 2)
    local v171 = value15_4("UIListLayout", {
		SortOrder = "LayoutOrder",
		VerticalAlignment = "Center",
		Padding = uDim
	})
    local value15_5 = t1.value15
    local uDim3 = UDim.new(0, 5)
    local uDim4 = UDim.new(0, 5)
    local v175 = value15_3("Frame", v164, t10, {
		v171,
		value15_5("UIPadding", {
			PaddingBottom = uDim3,
			PaddingTop = uDim4
		}),
		v155,
		v163
	})
    local t11 = {
		SetTitle = function(_, p71)
        if type(p71) == "string" and p71:gsub(" ", ""):len() > 0 then
            v155.Text = p71
        end
    end,
		SetDesc = function(_, p73)
        if type(p73) == "string" and p73:gsub(" ", ""):len() > 0 then
            v163.Visible = true
            v163.Text = p73
            v175.Position = UDim2.new(0, 10, 0)
            v175.AnchorPoint = Vector2.new(0, 0)

            return
        end

        v163.Visible = false
        v163.Text = ""
        v175.Position = UDim2.new(0, 10, 0.5)
        v175.AnchorPoint = Vector2.new(0, 0.5)
    end
	}

    t11:SetTitle(p66)
    t11:SetDesc(p67)

    if p69 and t1.value35[p69] then
        table.insert(t1.value35[p69], {
			Title = v155,
			Desc = v163
		})
    end

    return v164, t11
end
function t1.value37(p74)
    if p74:IsA("Frame") then
        return "BackgroundColor3"
    end

    if p74:IsA("ImageLabel") then
        return "ImageColor3"
    end

    if p74:IsA("TextLabel") then
        return "TextColor3"
    end

    if p74:IsA("ScrollingFrame") then
        return "ScrollBarImageColor3"
    end

    if p74:IsA("UIStroke") then
        return "Color"
    end

    return ""
end
function t1.value7.GetIcon(p75, p76)
    local v179 = type(p76) ~= "string"
    if not v179 then
        v179 = p76:find("rbxassetid://") or #p76 == 0
    end
    if v179 then
        return p76
    end
    local v180
    local v181 = string.lower(p76):gsub("lucide", ""):gsub("-", "")
    if p75.Icons[v181] then
        return p75.Icons[v181]
    end
    local Icons = p75.Icons
    local v183
    while true do
        local v184

        v183, v184 = Icons(nil, v183)

        if not v183 then
            break
        end

        if v183 == v181 then
            return v184
        end

        if not v180 and v183:find(v181, 1, true) then
            v180 = v184
        end
    end

    return v180 or v181
end
function t1.value7.SetTheme(_, p78)
    if not t1.value30(p78) then
        return
    end

    t1.value7.Save.Theme = p78
    t1.value31("redz library V5.json", t1.value7.Save)
    t1.value32 = t1.value7.Themes[p78]
    t1.value18:FireConnection("ThemeChanged", p78)

    for _, v in pairs(t1.value7.Instances) do
        if v.Type == "Gradient" then
            v.Instance.Color = t1.value32["Color Hub 1"]
        elseif v.Type == "Frame" then
            v.Instance.BackgroundColor3 = t1.value32["Color Hub 2"]
        elseif v.Type == "Stroke" then
            v.Instance[t1.value37(v.Instance)] = t1.value32["Color Stroke"]
        elseif v.Type == "Theme" then
            v.Instance[t1.value37(v.Instance)] = t1.value32["Color Theme"]
        elseif v.Type == "Text" then
            v.Instance[t1.value37(v.Instance)] = t1.value32["Color Text"]
        elseif v.Type == "DarkText" then
            v.Instance[t1.value37(v.Instance)] = t1.value32["Color Dark Text"]
        elseif v.Type == "ScrollBar" then
            v.Instance[t1.value37(v.Instance)] = t1.value32["Color Theme"]
        end
    end
end
function t1.value7.SetScale(_, p80)
    local v191 = t1.value8.Y / math.clamp(p80, 300, 2000)
    local value22Scale = t1.value22.Scale

    t1.value9 = v191
    value22Scale.Scale = v191
end
function t1.value7.MakeWindow(_, p82)
    local t12 = {}
    local v196 = p82[1]
    if not v196 then
        v196 = p82.Name

        if not v196 then
            v196 = p82.Title or "redz Library V5"
        end
    end
    local v197 = p82[2]
    if not v197 then
        v197 = p82.SubTitle or "by : redz9999"
    end
    t1.value10.ScriptFile = p82[3] or (p82.SaveFolder or false)
    local Logo = p82.Logo
    if not Logo then
        Logo = p82.Icon or p82.Image
    end
    local v199 = p82.TitleSize or 14;
    (function()
        local ScriptFile = t1.value10.ScriptFile

        if type(ScriptFile) ~= "string" then
            return
        end

        if not readfile or not isfile then
            return
        end

        local ok, result = pcall(isfile, ScriptFile)

        if ok and result then
            local ok2, result2 = pcall(readfile, ScriptFile)
            local v355 = result2

            if ok2 then
                ok2 = type(v355) == "string"
            end

            if ok2 then
                local ok3, result3 = pcall(function()
                    return t1.value3:JSONDecode(v355)
                end)

                t1.value11 = ok3 and result3 or {}
            end
        end
    end)()
    local v200, v201 = unpack(t1.value7.Save.UISize)
    local value13 = t1.value13
    local value15 = t1.value15
    local value22 = t1.value22
    local uDim2 = UDim2.fromOffset(v200, v201)
    local uDim2_7 = UDim2.new(0.5, -v200 / 2, 0.5, -v201 / 2)
    t12.value1 = value13(value15("ImageButton", value22, {
		Size = uDim2,
		Position = uDim2_7,
		BackgroundTransparency = 0.03,
		Name = "Hub"
	}), "Main")
    t1.value33("Gradient", t12.value1, {
		Rotation = 45
	})
    local value1 = t12.value1
    task.spawn(function()
        t1.value12(value1, {
			Active = true,
			AutoButtonColor = false
		})
        local value1Position
        local u359
        local function v360(p83)
            local v617 = p83.Position - nil
            local uDim2_8 = UDim2.new(value1Position.X.Scale, value1Position.X.Offset + v617.X / t1.value9, value1Position.Y.Scale, value1Position.Y.Offset + v617.Y / t1.value9)

            t1.value29({
				value1,
				"Position",
				uDim2_8,
				0.35
			})
        end
        value1.MouseButton1Down:Connect(function()
            u359 = true
        end)
        value1.InputBegan:Connect(function(input)
            local v620 = input.UserInputType == Enum.UserInputType.MouseButton1

            if not v620 then
                v620 = input.UserInputType == Enum.UserInputType.Touch
            end

            if v620 then
                value1Position = value1.Position

                local _ = input.Position

                while t1.value1:IsMouseButtonPressed(Enum.UserInputType.MouseButton1) do
                    t1.value4.Heartbeat:Wait()

                    if u359 then
                        v360(input)
                    end
                end
            end
        end)
    end)
    t12.value2 = t1.value33("Corner", t12.value1)
    t12.value3 = 0.03
    t12.value4 = false
    t12.value5 = nil
    t12.value6 = Color3.fromRGB(255, 0, 0)
    t12.value7 = false
    local value15_6 = t1.value15
    local value1_2 = t12.value1
    local value6 = t12.value6
    local Border = Enum.ApplyStrokeMode.Border
    t12.value8 = value15_6("UIStroke", value1_2, {
		Color = value6,
		Thickness = 2,
		Transparency = 0.1,
		ApplyStrokeMode = Border
	})
    t12.value8.Enabled = false
    t12.value9 = {}
    t12.value10 = false
    function t12.value11()
        if t12.value5 then
            t12.value5:Disconnect()
        end

        t12.value8.Color = t12.value6
        t12.value8.Thickness = 2
        t12.value8.Transparency = 0.1
    end
    local color3_6 = Color3.fromRGB(255, 0, 0)
    local color3_7 = Color3.fromRGB(160, 0, 0)
    local color3_8 = Color3.fromRGB(255, 80, 80)
    local color3_9 = Color3.fromRGB(120, 0, 0)
    local color3_10 = Color3.fromRGB(255, 60, 100)
    local color3_11 = Color3.fromRGB(255, 140, 0)
    local color3_12 = Color3.fromRGB(200, 90, 0)
    local color3_13 = Color3.fromRGB(255, 220, 0)
    local color3_14 = Color3.fromRGB(200, 170, 0)
    local color3_15 = Color3.fromRGB(0, 200, 60)
    local color3_16 = Color3.fromRGB(0, 110, 30)
    local color3_17 = Color3.fromRGB(120, 255, 150)
    local color3_18 = Color3.fromRGB(80, 255, 0)
    local color3_19 = Color3.fromRGB(0, 90, 255)
    local color3_20 = Color3.fromRGB(0, 40, 160)
    local color3_21 = Color3.fromRGB(100, 180, 255)
    local color3_22 = Color3.fromRGB(150, 220, 255)
    local color3_23 = Color3.fromRGB(0, 220, 220)
    local color3_24 = Color3.fromRGB(150, 0, 220)
    local color3_25 = Color3.fromRGB(90, 0, 150)
    local color3_26 = Color3.fromRGB(200, 130, 255)
    local color3_27 = Color3.fromRGB(255, 0, 160)
    local color3_28 = Color3.fromRGB(255, 150, 220)
    local color3_29 = Color3.fromRGB(10, 10, 10)
    local color3_30 = Color3.fromRGB(30, 30, 30)
    local color3_31 = Color3.fromRGB(60, 60, 60)
    local color3_32 = Color3.fromRGB(80, 80, 80)
    local color3_33 = Color3.fromRGB(140, 140, 140)
    local color3_34 = Color3.fromRGB(200, 200, 200)
    local color3_35 = Color3.fromRGB(180, 180, 180)
    local color3_36 = Color3.fromRGB(230, 230, 230)
    local color3_37 = Color3.fromRGB(255, 255, 255)
    local color3_38 = Color3.fromRGB(255, 200, 60)
    local color3_39 = Color3.fromRGB(180, 0, 0)
    t12.value12 = {
		Vermelho = color3_6,
		["Vermelho Escuro"] = color3_7,
		["Vermelho Claro"] = color3_8,
		["Vermelho Sangue"] = color3_9,
		["Vermelho Rosado"] = color3_10,
		Laranja = color3_11,
		["Laranja Escuro"] = color3_12,
		Amarelo = color3_13,
		["Amarelo Escuro"] = color3_14,
		Verde = color3_15,
		["Verde Escuro"] = color3_16,
		["Verde Claro"] = color3_17,
		["Verde Neon"] = color3_18,
		Azul = color3_19,
		["Azul Escuro"] = color3_20,
		["Azul Claro"] = color3_21,
		["Azul Bebê"] = color3_22,
		Ciano = color3_23,
		Roxo = color3_24,
		["Roxo Escuro"] = color3_25,
		["Roxo Claro"] = color3_26,
		Rosa = color3_27,
		["Rosa Claro"] = color3_28,
		["Preto Escuro"] = color3_29,
		Preto = color3_30,
		["Preto Claro"] = color3_31,
		["Cinza Escuro"] = color3_32,
		Cinza = color3_33,
		["Cinza Claro"] = color3_34,
		["Branco Escuro"] = color3_35,
		Branco = color3_36,
		["Branco Claro"] = color3_37,
		Dourado = color3_38,
		Spectra = color3_39
	}
    local v246 = t1.value15("Folder", t12.value1, {
		Name = "Components"
	})
    t12.value13 = t1.value15("Folder", t1.value22, {
		Name = "Dropdown"
	})
    t12.value14 = t1.value15("Frame", v246, {
		Size = UDim2.new(1, 0, 0, 28),
		BackgroundTransparency = 1,
		Name = "Top Bar"
	})
    local v247
    if Logo and Logo ~= "" then
        local v248 = t1.value7:GetIcon(Logo) or Logo
        local value15_7 = t1.value15
        local value14 = t12.value14
        local uDim2_9 = UDim2.fromOffset(20, 20)
        local uDim2_10 = UDim2.new(0, 10, 0.5)
        local vector2 = Vector2.new(0, 0.5)

        v247 = value15_7("ImageLabel", value14, {
			Size = uDim2_9,
			Position = uDim2_10,
			AnchorPoint = vector2,
			BackgroundTransparency = 1,
			Image = v248,
			Name = "Logo"
		})
        t1.value33("Corner", v247, UDim.new(0, 4))
    end
    if v247 then
        v247 = 10 + v247.Size.X.Offset + 5
    end
    local v254 = v247 or 15
    local value13_3 = t1.value13
    local value15_8 = t1.value15
    local value14 = t12.value14
    local uDim2_11 = UDim2.new(0, v254, 0.5)
    local vector2 = Vector2.new(0, 0.5)
    local v260 = t1.value32["Color Text"]
    local GothamMedium = Enum.Font.GothamMedium
    local t13 = {
		Position = uDim2_11,
		AnchorPoint = vector2,
		AutomaticSize = "XY",
		Text = v196,
		TextXAlignment = "Left",
		TextSize = v199,
		TextColor3 = v260,
		BackgroundTransparency = 1,
		Font = GothamMedium,
		Name = "Title"
	}
    local value13_4 = t1.value13
    local value15_9 = t1.value15
    local uDim2_12 = UDim2.fromScale(0, 1)
    local vector2_3 = Vector2.new(0, 1)
    local uDim2_13 = UDim2.new(1, 5, 0.9)
    local v268 = t1.value32["Color Dark Text"]
    local Gotham = Enum.Font.Gotham
    t12.value15 = value13_3(value15_8("TextLabel", value14, t13, { value13_4(value15_9("TextLabel", {
		Size = uDim2_12,
		AutomaticSize = "X",
		AnchorPoint = vector2_3,
		Position = uDim2_13,
		Text = v197,
		TextColor3 = v268,
		BackgroundTransparency = 1,
		TextXAlignment = "Left",
		TextYAlignment = "Bottom",
		TextSize = 8,
		Font = Gotham,
		Name = "SubTitle"
	}), "DarkText") }), "Text")
    local value13_5 = t1.value13
    local value15_10 = t1.value15
    local uDim2_14 = UDim2.new(0, t1.value7.Save.TabSize, 1, -t12.value14.Size.Y.Offset)
    local v273 = t1.value32["Color Theme"]
    local uDim2_15 = UDim2.new(0, 0, 1, 0)
    local vector2_4 = Vector2.new(0, 1)
    local uDim2_16 = UDim2.new()
    local t14 = {
		Size = uDim2_14,
		ScrollBarImageColor3 = v273,
		Position = uDim2_15,
		AnchorPoint = vector2_4,
		ScrollBarThickness = 1.5,
		BackgroundTransparency = 1,
		ScrollBarImageTransparency = 0.2,
		CanvasSize = uDim2_16,
		AutomaticCanvasSize = "Y",
		ScrollingDirection = "Y",
		BorderSizePixel = 0,
		Name = "Tab Scroll"
	}
    local value15_11 = t1.value15
    local uDim = UDim.new(0, 10)
    local uDim5 = UDim.new(0, 10)
    local uDim6 = UDim.new(0, 10)
    local uDim7 = UDim.new(0, 10)
    t12.value16 = value13_5(value15_10("ScrollingFrame", v246, t14, {
		value15_11("UIPadding", {
			PaddingLeft = uDim,
			PaddingRight = uDim5,
			PaddingTop = uDim6,
			PaddingBottom = uDim7
		}),
		t1.value15("UIListLayout", {
			Padding = UDim.new(0, 5)
		})
	}), "ScrollBar")
    local value15_12 = t1.value15
    local uDim2_17 = UDim2.new(1, -t12.value16.Size.X.Offset, 1, -t12.value14.Size.Y.Offset)
    local vector2_5 = Vector2.new(1, 1)
    local uDim2_18 = UDim2.new(1, 0, 1, 0)
    t12.value17 = value15_12("Frame", v246, {
		Size = uDim2_17,
		AnchorPoint = vector2_5,
		Position = uDim2_18,
		BackgroundTransparency = 1,
		ClipsDescendants = true,
		Name = "Containers"
	})
    t12.value18 = t1.value15("Frame", t12.value17, {
		Size = UDim2.new(1, 0, 1, 0),
		BackgroundTransparency = 1,
		Name = "ThemeParticles",
		ZIndex = -5,
		ClipsDescendants = true
	})
    t12.value19 = 0
    t12.value20 = 5
    t12.value21 = false
    t12.value22 = nil
    t12.value23 = 5
    t12.value24 = 7
    local value15_13 = t1.value15
    local value1_3 = t12.value1
    local vector2_6 = Vector2.new(0.5, 0.5)
    local uDim2_19 = UDim2.new(0.5, 0, 0.5, 0)
    local uDim2_20 = UDim2.fromOffset(120, 120)
    local Fit = Enum.ScaleType.Fit
    t12.value25 = value15_13("ImageLabel", value1_3, {
		Name = "RotatingLua",
		AnchorPoint = vector2_6,
		Position = uDim2_19,
		Size = uDim2_20,
		BackgroundTransparency = 1,
		Image = "rbxassetid://88089337055314",
		ImageTransparency = 0.3,
		ScaleType = Fit,
		ZIndex = -1,
		Visible = false
	})
    function t12.value26()
        local v365 = 50 + (t12.value23 - 1) * 50

        t12.value25.Size = UDim2.fromOffset(v365, v365)
        t12.value25.Position = UDim2.new(0.5, 0, 0.5, 0)
        t12.value25.AnchorPoint = Vector2.new(0.5, 0.5)

        local v366 = (t12.value23 - 1) / 19 * 0.4
        local v367 = 1 - (t12.value24 - 1) / 9

        t12.value25.ImageTransparency = math.clamp(v367 - v366, 0, 1)
    end
    t12.value1:GetPropertyChangedSignal("AbsoluteSize"):Connect(t12.value26)
    task.defer(function()
        t12.value26()

        local v370 = (t12.value23 - 1) / 19 * 0.4
        local v371 = 1 - (t12.value24 - 1) / 9

        t12.value25.ImageTransparency = math.clamp(v371 - v370, 0, 1)
    end)
    function t12.value27()
        if t12.value22 then
            return
        end

        t12.value22 = t1.value4.RenderStepped:Connect(function(dt)
            if t12.value20 > 0 then
                t12.value19 = (t12.value19 + t12.value20 * 10 * dt) % 360
                t12.value25.Rotation = t12.value19
            end
        end)
    end
    function t12.value28()
        if t12.value22 then
            t12.value22:Disconnect()
        end
    end
    t12.value29 = false
    local value15_14 = t1.value15
    local value14_2 = t12.value14
    local uDim2_21 = UDim2.fromOffset(90, 90)
    local uDim2_22 = UDim2.new(0, -10, 0, -20)
    local vector2_7 = Vector2.new(0.5, 0.5)
    local Fit2 = Enum.ScaleType.Fit
    t12.value30 = value15_14("ImageLabel", value14_2, {
		Name = "CornerSkull",
		Size = uDim2_21,
		Position = uDim2_22,
		AnchorPoint = vector2_7,
		BackgroundTransparency = 1,
		Image = "rbxassetid://91335483187539",
		ScaleType = Fit2,
		ZIndex = 100,
		Visible = false
	})
    local t15 = {
		Min = 6,
		Max = 14
	}
    local t16 = {
		Min = 20,
		Max = 35
	}
    t12.value31 = {
		MaxParticles = 30,
		SpawnRate = 0.12,
		ParticleSize = t15,
		ParticleSpeed = t16,
		ParticleLifetime = 5
	}
    t12.value32 = "Vermelho"
    t12.value33 = false
    t12.value34 = {}
    t12.value35 = 0
    t12.value36 = nil
    local t17 = { Color3.fromRGB(255, 0, 0) }
    local t18 = { Color3.fromRGB(30, 30, 30) }
    local t19 = { Color3.fromRGB(180, 0, 0) }
    local t20 = { Color3.fromRGB(0, 60, 255) }
    local t21 = { Color3.fromRGB(0, 180, 255) }
    local t22 = { Color3.fromRGB(100, 200, 255) }
    local t23 = { Color3.fromRGB(255, 0, 160) }
    local t24 = { Color3.fromRGB(255, 255, 255) }
    local t25 = { Color3.fromRGB(160, 160, 160) }
    local t26 = {
		Color3.fromRGB(180, 0, 0),
		Color3.fromRGB(160, 160, 160),
		Color3.fromRGB(30, 30, 30)
	}
    t12.value37 = {
		Vermelho = t17,
		Preto = t18,
		["Vermelho Escuro"] = t19,
		Azul = t20,
		["Azul Claro"] = t21,
		["Azul BebÃª"] = t22,
		Rosa = t23,
		Branco = t24,
		Cinza = t25,
		Spectra = t26,
		RGB = "rainbow"
	}
    t12.value38 = 0
    function t12.value39()
        local v372 = t12.value37[t12.value32]

        if v372 == "rainbow" then
            return Color3.fromRGB(math.random(0, 255), math.random(0, 255), math.random(0, 255))
        end

        if type(v372) == "table" then
            if #v372 == 1 then
                return v372[1]
            end

            local v373 = #v372

            t12.value38 = t12.value38 % v373 + 1

            return v372[t12.value38]
        end

        return Color3.fromRGB(220, 0, 0)
    end
    function t12.value40()
        if #t12.value34 >= t12.value31.MaxParticles then
            return
        end

        local AbsoluteSize = t12.value18.AbsoluteSize
        local v375 = math.random(10, (math.max(10, AbsoluteSize.X - 10)))
        local v376 = AbsoluteSize.Y + 20
        local v377 = math.random(t12.value31.ParticleSize.Min, t12.value31.ParticleSize.Max)
        local v378 = math.random(t12.value31.ParticleSpeed.Min, t12.value31.ParticleSpeed.Max)
        local v379 = t12.value39()
        local value15_15 = t1.value15
        local value18 = t12.value18
        local uDim2_23 = UDim2.fromOffset(v377, v377)
        local uDim2_24 = UDim2.fromOffset(v375, v376)
        local v384 = value15_15("Frame", value18, {
			Size = uDim2_23,
			Position = uDim2_24,
			BackgroundColor3 = v379,
			BackgroundTransparency = 0,
			BorderSizePixel = 0,
			ZIndex = -3
		})

        t1.value15("UICorner", v384, {
			CornerRadius = UDim.new(0.5, 0)
		})

        local value15_16 = t1.value15
        local uDim2_25 = UDim2.new(1, 8, 1, 8)
        local uDim2_26 = UDim2.new(0.5, 0, 0.5, 0)
        local vector2_8 = Vector2.new(0.5, 0.5)
        local v389 = value15_16("Frame", v384, {
			Size = uDim2_25,
			Position = uDim2_26,
			AnchorPoint = vector2_8,
			BackgroundColor3 = v379,
			BackgroundTransparency = 0.4,
			ZIndex = -3
		})

        t1.value15("UICorner", v389, {
			CornerRadius = UDim.new(0.5, 0)
		})

        local timestamp = tick()
        local vector2_9 = Vector2.new(0, -v378)
        local t27 = {
			Frame = v384,
			Glow = v389,
			StartTime = timestamp,
			Speed = v378,
			Direction = vector2_9,
			OriginalColor = v379
		}

        v384.BackgroundTransparency = 1
        v389.BackgroundTransparency = 1
        t1.value29({
			v384,
			"BackgroundTransparency",
			0,
			0.3
		})
        t1.value29({
			v389,
			"BackgroundTransparency",
			0.3,
			0.3
		})
        table.insert(t12.value34, t27)
    end
    function t12.value41()
        for i = #t12.value34, 1, -1 do
            local v394 = i
            local v395 = t12.value34[v394]
            local v396 = tick() - v395.StartTime
            local v397 = v396 >= t12.value31.ParticleLifetime

            if not v397 then
                v397 = v395.Frame.Position.Y.Offset < -20
            end

            if v397 then
                t1.value29({
					v395.Frame,
					"BackgroundTransparency",
					1,
					0.5
				})
                t1.value29({
					v395.Glow,
					"BackgroundTransparency",
					1,
					0.5
				})
                task.spawn(function()
                    task.wait(0.5)

                    local Frame = v395.Frame

                    if Frame then
                        Frame = v395.Frame.Parent
                    end

                    if Frame then
                        v395.Frame:Destroy()
                    end
                end)
                table.remove(t12.value34, v394)
            else
                local FramePosition = v395.Frame.Position
                local v399 = FramePosition.Y.Offset + v395.Direction.Y * 0.016

                v395.Frame.Position = UDim2.fromOffset(FramePosition.X.Offset, v399)

                local v400 = v396 / t12.value31.ParticleLifetime

                if v400 > 0.75 then
                    local v401 = 1 - (v400 - 0.75) / 0.25

                    v395.Frame.BackgroundTransparency = math.clamp(1 - v401, 0, 1)
                    v395.Glow.BackgroundTransparency = math.clamp(0.4 + (1 - v401) * 0.6, 0, 1)
                end
            end
        end
    end
    local function v311()
        if t12.value36 then
            t12.value36:Disconnect()
        end

        for _, v in ipairs(t12.value34) do
            local Frame = v.Frame

            if Frame then
                Frame = v.Frame.Parent
            end

            if Frame then
                v.Frame:Destroy()
            end
        end
    end
    local v312 = v15
    local value15_17 = t1.value15
    local value1_4 = t12.value1
    local uDim2_27 = UDim2.new(0, 35, 0, 35)
    local value1Size = t12.value1.Size
    local vector2_10 = Vector2.new(0.8, 0.8)
    local t28 = { value15_17("ImageButton", value1_4, {
		Size = uDim2_27,
		Position = value1Size,
		Active = true,
		AnchorPoint = vector2_10,
		BackgroundTransparency = 1,
		Name = "Control Hub Size"
	}) }
    t12.value42 = v312(v2(t28))
    local v319 = v15
    local value15_18 = t1.value15
    local value1_5 = t12.value1
    local uDim2_28 = UDim2.new(0, 20, 1, -30)
    local uDim2_29 = UDim2.new(0, t12.value16.Size.X.Offset, 1, 0)
    local vector2_11 = Vector2.new(0.5, 1)
    local v325 = v319(value15_18("ImageButton", value1_5, {
		Size = uDim2_28,
		Position = uDim2_29,
		AnchorPoint = vector2_11,
		Active = true,
		BackgroundTransparency = 1,
		Name = "Control Tab Size"
	}))
    t12.value43 = nil
    t12.value43 = v325
    local function v326()
        local value42Position = t12.value42.Position
        local value43Position = t12.value43.Position

        t12.value42.Position = UDim2.fromOffset(math.clamp(value42Position.X.Offset, 430, 1000), (math.clamp(value42Position.Y.Offset, 200, 500)))
        t12.value43.Position = UDim2.new(0, math.clamp(value43Position.X.Offset, 135, 250), 1, 0)
        t12.value16.Size = UDim2.new(0, t12.value43.Position.X.Offset, 1, -t12.value14.Size.Y.Offset)
        t12.value17.Size = UDim2.new(1, -t12.value16.Size.X.Offset, 1, -t12.value14.Size.Y.Offset)
        t12.value1.Size = t12.value42.Position
    end
    t12.value42:GetPropertyChangedSignal("Position"):Connect(v326)
    t12.value43:GetPropertyChangedSignal("Position"):Connect(v326)
    t1.value28(t12.value42, function()
        if not Minimized then
            t1.value7.Save.UISize = {
				t12.value1.Size.X.Offset,
				t12.value1.Size.Y.Offset
			}
            t1.value31("redz library V5.json", t1.value7.Save)
        end
    end)
    t1.value28(t12.value43, function()
        t1.value7.Save.TabSize = t12.value16.Size.X.Offset
        t1.value31("redz library V5.json", t1.value7.Save)
    end)
    local v327 = t1.value15("Folder", t12.value14, {
		Name = "Buttons"
	})
    local value15_19 = t1.value15
    local uDim2_30 = UDim2.new(0, 14, 0, 14)
    local uDim2_31 = UDim2.new(1, -10, 0.5)
    local vector2_12 = Vector2.new(1, 0.5)
    local v332 = value15_19("ImageButton", {
		Size = uDim2_30,
		Position = uDim2_31,
		AnchorPoint = vector2_12,
		BackgroundTransparency = 1,
		Image = "rbxassetid://10747384394",
		AutoButtonColor = false,
		Name = "Close"
	})
    t12.value44 = t1.value12(v332:Clone(), {
		Position = UDim2.new(1, -35, 0.5),
		Image = "rbxassetid://10734896206",
		Name = "Minimize"
	})
    local t29 = {
		v332,
		t12.value44
	}
    t1.value14(v327, t29)
    t12.value45 = nil
    t12.value46 = nil
    t12.value47 = nil
    t12.value48 = nil
    t12.value49 = {}
    t12.value50 = false
    function t12.value49.CloseBtn(_)
        t12.value49:Dialog({
			Title = "Close",
			Text = "Are you sure you want to close Spectra Hub? Some bugs may occur if any feature is still enabled.",
			Options = {
				{
					"Confirm",
					function()
            v311()
            t12.value28()
            t1.value22:Destroy()
        end
				},
				{ "Cancel" }
			}
		})
    end
    function t12.value49.MinimizeBtn(_)
        if t12.value47 then
            return
        end

        if t12.value45 then
            t12.value44.Image = "rbxassetid://10734896206"
            t1.value29({
				t12.value1,
				"Size",
				t12.value46,
				0.25,
				true
			})
            t12.value42.Visible = true
            t12.value43.Visible = true

            if t12.value21 then
                t12.value25.Visible = true
            end

            t12.value45 = false

            return
        end

        t12.value44.Image = "rbxassetid://10734924532"

        local _ = t12.value1.Size

        t12.value42.Visible = false
        t12.value43.Visible = false
        t12.value25.Visible = false
        t1.value29({
			t12.value1,
			"Size",
			UDim2.fromOffset(t12.value1.Size.X.Offset, 28),
			0.25,
			true
		})
        t12.value45 = true
    end
    function t12.value49.Minimize(_)
        t12.value1.Visible = not t12.value1.Visible
    end
    function t12.value49.AddMinimizeButton(_, p88)
        local v414 = v15
        local value15_20 = t1.value15
        local value22_2 = t1.value22
        local uDim2_32 = UDim2.fromOffset(35, 35)
        local uDim2_33 = UDim2.fromScale(0.15, 0.15)
        local v419 = t1.value32["Color Hub 2"]
        local v420 = v414(value15_20("ImageButton", value22_2, {
			Size = uDim2_32,
			Position = uDim2_33,
			BackgroundTransparency = 1,
			BackgroundColor3 = v419,
			AutoButtonColor = false
		}))
    local v421
        local v422
        if p88.Corner then
            v421 = t1.value33("Corner", v420)
            t1.value12(v421, p88.Corner)
        end
        if p88.Stroke then
            v422 = t1.value33("Stroke", v420)
            t1.value12(v422, p88.Stroke)
        end
        t1.value12(v420, p88.Button)
        v420.Activated:Connect(t12.value49.Minimize)
        t12.value48 = v420

        return {
			Stroke = v422,
			Corner = v421,
			Button = v420
		}
    end
    function t12.value49.SetMinimizeButtonImage(_, p90)
        if not t12.value48 then
            return
        end

        local _tostring = tostring

        if not p90 then
            p90 = ""
        end

        local v426 = _tostring(p90)

        if v426 == "" then
            return
        end

        t12.value48.Image = v426:find("rbxassetid://") and v426 or "rbxassetid://" .. v426
    end
    function t12.value49.SetMinimizeButtonSize(_, p92)
        if not t12.value48 then
            return
        end

        local v429 = tonumber(p92) or 35

        t12.value48.Size = UDim2.fromOffset(v429, v429)
    end
    function t12.value49.SetMinimizeButtonTransparent(_, p94)
        if not t12.value48 then
            return
        end

        t12.value48.BackgroundTransparency = not p94 and 0 or 1
    end
    function t12.value49.SetWindowTransparency(_, p96)
        t12.value3 = tonumber(p96) or 0.03
        t12.value1.BackgroundTransparency = t12.value3
    end
    function t12.value49.SetElementTextSize(_, p98, p99)
        if not t1.value35[p98] then
            return
        end

        local v437 = tonumber(p99) or 10

        t1.value34[p98] = v437

        local v438 = math.max(6, (math.floor(v437 * 0.8)))

        for _, v in ipairs(t1.value35[p98]) do
            if v.Title then
                v.Title.TextSize = v437
            end

            if v.Desc then
                v.Desc.TextSize = v438
            end

            if v.Label then
                v.Label.TextSize = v437
            end
        end
    end
    function t12.value49.SetGlow(_, p101)
        t12.value4 = p101
        t12.value8.Enabled = p101

        if p101 then
            if t12.value5 then
                return
            end

            local n1 = 0

            t12.value5 = t1.value4.RenderStepped:Connect(function(dt)
                n1 += dt

                if t12.value7 then
                    local v629 = (math.sin(n1 * 5.235987755982989) + 1) / 2

                    t12.value8.Thickness = 2 + v629 * 4.5
                    t12.value8.Transparency = 0 + (1 - v629) * 0.08

                    return
                end

                local v630 = (math.sin(n1 * 2.0943951023931953) + 1) / 2

                t12.value8.Thickness = 1.8 + v630 * 1.4
                t12.value8.Transparency = 0.05 + (1 - v630) * 0.2
            end)

            return
        end

        t12.value11()
    end
    function t12.value49.SetGlowColor(_, p103)
        local v446 = t12.value12[p103]

        if v446 then
            t12.value6 = v446
            t12.value8.Color = v446

            for _, v in ipairs(t12.value9) do
                v.Color = v446
            end
        end
    end
    function t12.value49.SetGlowIntensity(_, p105)
        t12.value7 = not not p105
    end
    function t12.value49.SetTabGlow(_, p107)
        t12.value10 = not not p107

        for _, v in ipairs(t12.value9) do
            v.Enabled = t12.value10
        end
    end
    function t12.value49.SetSound(_, p109)
        t1.value23 = not not p109
    end
    function t12.value49.SetSoundId(_, p111)
        local _tostring = tostring

        if not p111 then
            p111 = ""
        end

        local v460 = _tostring(p111)
        local v461 = v460 ~= ""

        if v461 then
            v461 = not v460:find("rbxassetid://")
        end

        if v461 then
            v460 = "rbxassetid://" .. v460
        end

        t1.value24 = v460
    end
    function t12.value49.SetParticles(_, p113)
        t12.value33 = p113

        if p113 then
            if t12.value36 then
                return
            end

            t12.value36 = t1.value4.Heartbeat:Connect(function()
                t12.value41()

                local v631 = tick() - t12.value35 >= t12.value31.SpawnRate

                if v631 then
                    v631 = t12.value1.Visible
                end

                if v631 then
                    t12.value40()
                    tick()
                end
            end)

            return
        end

        v311()
    end
    function t12.value49.SetParticleColor(_, p115)
        if t12.value37[p115] then
            t12.value32 = p115

            if t12.value33 then
                v311()

                if t12.value36 then
                    return
                end

                t12.value36 = t1.value4.Heartbeat:Connect(function()
                    t12.value41()

                    local v632 = tick() - t12.value35 >= t12.value31.SpawnRate

                    if v632 then
                        v632 = t12.value1.Visible
                    end

                    if v632 then
                        t12.value40()
                        tick()
                    end
                end)
            end
        end
    end
    function t12.value49.SetLua(_, p117)
        t12.value21 = p117
        t12.value25.Visible = p117

        if p117 then
            t12.value26()

            local v468 = (t12.value23 - 1) / 19 * 0.4
            local v469 = 1 - (t12.value24 - 1) / 9

            t12.value25.ImageTransparency = math.clamp(v469 - v468, 0, 1)
            t12.value27()

            return
        end

        t12.value28()
    end
    function t12.value49.SetLuaImage(_, p119)
        local _tostring = tostring

        if not p119 then
            p119 = ""
        end

        local v473 = _tostring(p119)

        if v473 == "" then
            t12.value25.Image = ""

            return
        end

        t12.value25.Image = v473:find("rbxassetid://") and v473 or "rbxassetid://" .. v473
    end
    function t12.value49.SetLuaSpeed(_, p121)
        t12.value20 = tonumber(p121) or 5
    end
    function t12.value49.SetLuaSize(_, p123)
        t12.value23 = tonumber(p123) or 5

        if t12.value21 then
            t12.value26()
        end
    end
    function t12.value49.SetLuaBrightness(_, p125)
        t12.value24 = tonumber(p125) or 5

        local v480 = (t12.value23 - 1) / 19 * 0.4
        local v481 = 1 - (t12.value24 - 1) / 9

        t12.value25.ImageTransparency = math.clamp(v481 - v480, 0, 1)
    end
    function t12.value49.SetSkull(_, p127)
        t12.value29 = p127
        t12.value30.Visible = p127
    end
    function t12.value49.SetSkullImage(_, p129)
        local _tostring = tostring

        if not p129 then
            p129 = ""
        end

        local v487 = _tostring(p129)

        if v487 == "" then
            t12.value30.Image = ""

            return
        end

        t12.value30.Image = v487:find("rbxassetid://") and v487 or "rbxassetid://" .. v487
    end
    function t12.value49.SetBackground(_, p131)
        if not p131 or p131 == "" then
            t12.value1.Image = ""
            t12.value1.ImageTransparency = 1

            for _, v in pairs(t1.value7.Instances) do
                local v492 = v.Type == "Gradient"

                if v492 then
                    v492 = v.Instance.Parent == t12.value1
                end

                if v492 then
                    v.Instance.Enabled = true
                end
            end

            return
        end

        local str = tostring(p131)

        t12.value1.Image = str:find("rbxassetid://") and str or "rbxassetid://" .. str
        t12.value1.ImageTransparency = 0.2
        t12.value1.ScaleType = Enum.ScaleType.Crop

        for _, v in pairs(t1.value7.Instances) do
            local v496 = v.Type == "Gradient"

            if v496 then
                v496 = v.Instance.Parent == t12.value1
            end

            if v496 then
                v.Instance.Enabled = false
            end
        end
    end
    function t12.value49.Set(_, p133, p134)
        local v500 = type(p133) == "string"

        if v500 then
            v500 = type(p134) == "string"
        end

        if v500 then
            t12.value15.Text = p133
            t12.value15.SubTitle.Text = p134

            return
        end

        if type(p133) == "string" then
            t12.value15.Text = p133
        end
    end
    function t12.value49.Dialog(_, p136)
        if t12.value1:FindFirstChild("Dialog") then
            return
        end

        if t12.value45 then
            t12.value49:MinimizeBtn()
        end

        local v503 = p136[1]

        if not v503 then
            v503 = p136.Title or "Dialog"
        end

        local v504 = p136[2]

        if not v504 then
            v504 = p136.Text or "This is a Dialog"
        end

        local v505 = p136[3]

        if not v505 then
            v505 = p136.Options or {}
        end

        local value15_21 = t1.value15
        local uDim2_34 = UDim2.fromOffset(270, 162)
        local uDim2_35 = UDim2.fromScale(0.5, 0.5)
        local vector2_13 = Vector2.new(0.5, 0.5)
        local t30 = {
			Active = true,
			Size = uDim2_34,
			Position = uDim2_35,
			AnchorPoint = vector2_13
		}
    local value13_6 = t1.value13
        local value15_22 = t1.value15
        local GothamBold = Enum.Font.GothamBold
        local uDim2_36 = UDim2.new(1, 0, 0, 20)
        local v515 = t1.value32["Color Text"]
        local uDim2_37 = UDim2.fromOffset(15, 5)
        local v517 = value13_6(value15_22("TextLabel", {
			Font = GothamBold,
			Size = uDim2_36,
			Text = v503,
			TextXAlignment = "Left",
			TextColor3 = v515,
			TextSize = 15,
			Position = uDim2_37,
			BackgroundTransparency = 1
		}), "Text")
        local value13_7 = t1.value13
        local value15_23 = t1.value15
        local GothamMedium2 = Enum.Font.GothamMedium
        local uDim2_38 = UDim2.new(1, -25)
        local v522 = t1.value32["Color Dark Text"]
        local uDim2_39 = UDim2.fromOffset(15, 25)
        local v524 = value15_21("Frame", t30, {
			v517,
			value13_7(value15_23("TextLabel", {
				Font = GothamMedium2,
				Size = uDim2_38,
				AutomaticSize = "Y",
				Text = v504,
				TextXAlignment = "Left",
				TextColor3 = v522,
				TextSize = 12,
				Position = uDim2_39,
				BackgroundTransparency = 1,
				TextWrapped = true
			}), "DarkText")
		})

        t1.value33("Gradient", v524, {
			Rotation = 270
		})
        t1.value33("Corner", v524)

        local value15_24 = t1.value15
        local uDim2_40 = UDim2.fromScale(1, 0.35)
        local uDim2_41 = UDim2.fromScale(0, 1)
        local vector2_14 = Vector2.new(0, 1)
        local v529 = t1.value32["Color Hub 2"]
        local v530 = value15_24("Frame", v524, {
			Size = uDim2_40,
			Position = uDim2_41,
			AnchorPoint = vector2_14,
			BackgroundColor3 = v529,
			BackgroundTransparency = 1
		}, { t1.value15("UIListLayout", {
			Padding = UDim.new(0, 10),
			VerticalAlignment = "Center",
			FillDirection = "Horizontal",
			HorizontalAlignment = "Center"
		}) })
        local value13_8 = t1.value13
        local value15_25 = t1.value15
        local value1_6 = t12.value1
        local v534 = t1.value32["Color Hub 2"]
        local uDim2_42 = UDim2.new(1, 0, 1, 0)
        local v536 = t1.value32["Color Stroke"]
        local v537 = value13_8(value15_25("Frame", value1_6, {
			BackgroundTransparency = 0.6,
			Active = true,
			BackgroundColor3 = v534,
			Size = uDim2_42,
			BackgroundColor3 = v536,
			Name = "Dialog"
		}), "Stroke")

        t12.value2:Clone().Parent = v537
        v524.Parent = v537
        t1.value29({
			v524,
			"Size",
			UDim2.fromOffset(250, 150),
			0.2
		})
        t1.value29({
			v524,
			"Transparency",
			0,
			0.15
		})
        t1.value29({
			v537,
			"Transparency",
			0.3,
			0.15
		})

        local n2 = 1
        local t31 = {}

        function t31.Button(_, p138)
            local v635 = p138[1]

            if not v635 then
                v635 = p138.Name

                if not v635 then
                    v635 = p138.Title or ""
                end
            end

            local v636 = p138[2]

            if not v636 then
                v636 = p138.Callback or function()
                end
            end

            n2 += 1

            local v637 = t1.value33("Button", v530)

            t1.value33("Corner", v637)

            local value12 = t1.value12
            local GothamBold2 = Enum.Font.GothamBold
            local v640 = t1.value32["Color Text"]

            value12(v637, {
				Text = v635,
				Font = GothamBold2,
				TextColor3 = v640,
				TextSize = 12
			})

            for _, child in pairs(v530:GetChildren()) do
                if child:IsA("TextButton") then
                    child.Size = UDim2.new(1 / n2, -((n2 - 1) * 20 / n2), 0, 32)
                end
            end

            v637.Activated:Connect(t31.Close)
            v637.Activated:Connect(v636)
        end
        function t31.Close(_)
            t1.value29({
				v524,
				"Size",
				UDim2.fromOffset(270, 162),
				0.2
			})
            t1.value29({
				v537,
				"Transparency",
				1,
				0.15
			})
            t1.value29({
				v524,
				"Transparency",
				1,
				0.15,
				true
			})
            v537:Destroy()
        end

        for _, v in ipairs(v505) do
            t31:Button(v)
        end

        return t31
    end
    function t12.value49.SelectTab(_, p141)
        if type(p141) == "number" then
            t1.value7.Tabs[p141].func:Enable()

            return
        end

        for _, v in pairs(t1.value7.Tabs) do
            if v.Cont == p141.Cont then
                v.func:Enable()
            end
        end
    end
    t12.value51 = {}
    t12.value52 = false
    t12.value53 = {}
    t12.value54 = {}
    function t12.value49.SetSectionIndicator(_, p143)
        t12.value52 = p143
        for v550, v551 in ipairs(t12.value53) do

            v551.BackgroundTransparency = not p143 and 1 or 0
        end
        for _, v in ipairs(t12.value54) do
            local vLabel = v.Label
            local v555 = p143

            if p143 then
                v555 = UDim2.new(0, 10)
            end

            if not v555 then
                v555 = UDim2.new(0, 5)
            end

            vLabel.Position = v555
        end
    end
    function t12.value49.MakeTab(_, p145, p146)
        if type(p145) == "table" then
            p146 = p145
        end

        local v559 = p146[1]

        if not v559 then
            v559 = p146.Title or "Tab!"
        end

        local v560 = p146[2]

        if not v560 then
            v560 = p146.Icon or ""
        end

        local Icon = t1.value7:GetIcon(v560)
        local v562 = not Icon:find("rbxassetid://")

        if not v562 then
            v562 = Icon:gsub("rbxassetid://", ""):len() < 6
        end

        if v562 then
            Icon = false
        end

        local v563 = t1.value33("Button", t12.value16, {
			Size = UDim2.new(1, 0, 0, 24)
		})

        t1.value33("Corner", v563)

        local value15_26 = t1.value15
        local value6_2 = t12.value6
        local value10 = t12.value10
        local Border2 = Enum.ApplyStrokeMode.Border
        local v568 = value15_26("UIStroke", v563, {
			Color = value6_2,
			Thickness = 1.5,
			Transparency = 0.1,
			Enabled = value10,
			ApplyStrokeMode = Border2
		})

        table.insert(t12.value9, v568)

        local value13_9 = t1.value13
        local value15_27 = t1.value15
        local uDim2_43 = UDim2.new(1, not Icon and -15 or -28, 1)
        local uDim2_44 = UDim2.fromOffset(not Icon and 15 or 28)
        local GothamMedium3 = Enum.Font.GothamMedium
        local v574 = t1.value32["Color Text"]
        local Left = Enum.TextXAlignment.Left
        local v576 = not t12.value50 and 0 or 0.3
        local v577 = value13_9(value15_27("TextLabel", v563, {
			Size = uDim2_43,
			Position = uDim2_44,
			BackgroundTransparency = 1,
			Font = GothamMedium3,
			Text = v559,
			TextColor3 = v574,
			TextSize = 10,
			TextXAlignment = Left,
			TextTransparency = v576,
			TextTruncate = "AtEnd"
		}), "Text")
        local value13_10 = t1.value13
        local value15_28 = t1.value15
        local uDim2_45 = UDim2.new(0, 7, 0.5)
        local uDim2_46 = UDim2.new(0, 17, 0, 17)
        local vector2_15 = Vector2.new(0, 0.5)
        local v583 = Icon or ""
        local v584 = not t12.value50 and 0 or 0.3
        local v585 = value13_10(value15_28("ImageLabel", v563, {
			Position = uDim2_45,
			Size = uDim2_46,
			AnchorPoint = vector2_15,
			Image = v583,
			BackgroundTransparency = 1,
			ImageTransparency = v584
		}), "Text")
        local value13_11 = t1.value13
        local value15_29 = t1.value15
        local value50 = t12.value50

        if value50 then
            value50 = UDim2.new(0, 4, 0, 4)
        end

        if not value50 then
            value50 = UDim2.new(0, 4, 0, 13)
        end

        local uDim2_47 = UDim2.new(0, 1, 0.5)
        local vector2_16 = Vector2.new(0, 0.5)
        local v591 = t1.value32["Color Theme"]
        local v592 = value13_11(value15_29("Frame", v563, {
			Size = value50,
			Position = uDim2_47,
			AnchorPoint = vector2_16,
			BackgroundColor3 = v591,
			BackgroundTransparency = not t12.value50 and 0 or 1
		}), "Theme")

        t1.value33("Corner", v592, UDim.new(0.5, 0))

        local value13_12 = t1.value13
        local value15_30 = t1.value15
        local uDim2_48 = UDim2.new(1, 0, 1, 0)
        local uDim2_49 = UDim2.new(0, 0, 1)
        local vector2_17 = Vector2.new(0, 1)
        local v598 = t1.value32["Color Theme"]
        local uDim2_50 = UDim2.new()
        local v600 = ("Container %i [ %s ]"):format(#t12.value51 + 1, v559)
        local t32 = {
			Size = uDim2_48,
			Position = uDim2_49,
			AnchorPoint = vector2_17,
			ScrollBarThickness = 1.5,
			BackgroundTransparency = 1,
			ScrollBarImageTransparency = 0.2,
			ScrollBarImageColor3 = v598,
			AutomaticCanvasSize = "Y",
			ScrollingDirection = "Y",
			BorderSizePixel = 0,
			CanvasSize = uDim2_50,
			Name = v600
		}
        local value15_31 = t1.value15
        local uDim8 = UDim.new(0, 10)
        local uDim9 = UDim.new(0, 10)
        local uDim10 = UDim.new(0, 10)
        local uDim11 = UDim.new(0, 10)
        local v607 = value13_12(value15_30("ScrollingFrame", t32, {
			value15_31("UIPadding", {
				PaddingLeft = uDim8,
				PaddingRight = uDim9,
				PaddingTop = uDim10,
				PaddingBottom = uDim11
			}),
			t1.value15("UIListLayout", {
				Padding = UDim.new(0, 5)
			})
		}), "ScrollBar")

        table.insert(t12.value51, v607)

        if not t12.value50 then
            v607.Parent = t12.value17
        end

        local function v608()
            if v607.Parent then
                return
            end

            for _, v in pairs(t12.value51) do
                local v646 = v:IsA("ScrollingFrame")

                if v646 then
                    v646 = v ~= v607
                end

                if v646 then
                    v.Parent = nil
                end
            end

            v607.Parent = t12.value17
            v607.Size = UDim2.new(1, 0, 1, 150)

            for _, v in pairs(t1.value7.Tabs) do
                if v.Cont ~= v607 then
                    v.func:Disable()
                end
            end

            t1.value29({
				v607,
				"Size",
				UDim2.new(1, 0, 1, 0),
				0.3
			})
            t1.value29({
				v577,
				"TextTransparency",
				0,
				0.35
			})
            t1.value29({
				v585,
				"ImageTransparency",
				0,
				0.35
			})
            t1.value29({
				v592,
				"Size",
				UDim2.new(0, 4, 0, 13),
				0.35
			})
            t1.value29({
				v592,
				"BackgroundTransparency",
				0,
				0.35
			})
        end

        v563.Activated:Connect(v608)

        local t33 = {}

        table.insert(t1.value7.Tabs, {
			TabInfo = {
				Name = v559,
				Icon = Icon
			},
			func = t33,
			Cont = v607
		})
        t33.Cont = v607

        function t33.Disable(_)
            v607.Parent = nil
            t1.value29({
				v577,
				"TextTransparency",
				0.3,
				0.35
			})
            t1.value29({
				v585,
				"ImageTransparency",
				0.3,
				0.35
			})
            t1.value29({
				v592,
				"Size",
				UDim2.new(0, 4, 0, 4),
				0.35
			})
            t1.value29({
				v592,
				"BackgroundTransparency",
				1,
				0.35
			})
        end
        function t33.Enable(_)
            v608()
        end
        function t33.Visible(_, p150)
            t1.value16:ToggleVisible(v563, p150)
            t1.value16:ToggleParent(v607, p150, t12.value17)
        end
        function t33.Destroy(_)
            v563:Destroy()
            v607:Destroy()
        end
        function t33.AddSection(_, p153)
            local v656 = type(p153) == "string" and p153

            if not v656 then
                v656 = p153[1]

                if not v656 then
                    v656 = p153.Name

                    if not v656 then
                        v656 = p153.Title or p153.Section
                    end
                end
            end

            local v657 = t1.value34.Section or 14
            local v658 = t1.value15("Frame", v607, {
				Size = UDim2.new(1, 0, 0, 20),
				BackgroundTransparency = 1,
				Name = "Option"
			})
            local value13_13 = t1.value13
            local value15_32 = t1.value15
            local uDim2_51 = UDim2.new(0, 4, 0, 13)
            local uDim2_52 = UDim2.new(0, 1, 0.5)
            local vector2_18 = Vector2.new(0, 0.5)
            local v664 = t1.value32["Color Theme"]
            local v665 = not t12.value52 and 1 or 0
            local v666 = value13_13(value15_32("Frame", v658, {
				Size = uDim2_51,
				Position = uDim2_52,
				AnchorPoint = vector2_18,
				BackgroundColor3 = v664,
				BackgroundTransparency = v665,
				Name = "SecIndicator"
			}), "Theme")

            t1.value15("UICorner", v666, {
				CornerRadius = UDim.new(0.5, 0)
			})
            table.insert(t12.value53, v666)

            local value13_14 = t1.value13
            local value15_33 = t1.value15
            local GothamBold = Enum.Font.GothamBold
            local v670 = t1.value32["Color Text"]
            local uDim2_53 = UDim2.new(1, -25, 0, 20)
            local value52 = t12.value52

            if value52 then
                value52 = UDim2.new(0, 10, 0, 0)
            end

            if not value52 then
                value52 = UDim2.new(0, 5, 0, 0)
            end

            local AutomaticSizeY = Enum.AutomaticSize.Y
            local v674 = value13_14(value15_33("TextLabel", v658, {
				Font = GothamBold,
				Text = v656,
				TextColor3 = v670,
				Size = uDim2_53,
				Position = value52,
				BackgroundTransparency = 1,
				TextWrapped = true,
				AutomaticSize = AutomaticSizeY,
				TextSize = v657,
				TextXAlignment = "Left",
				TextYAlignment = "Top"
			}), "Text")

            local function v675()
                v658.Size = UDim2.new(1, 0, 0, (math.max(20, v674.AbsoluteSize.Y)))
            end

            v674:GetPropertyChangedSignal("AbsoluteSize"):Connect(v675)
            task.defer(v675)
            table.insert(t1.value35.Section, {
				Label = v674,
				Title = v674
			})
            table.insert(t12.value54, {
				Label = v674,
				Indicator = v666
			})

            local t34 = {}

            table.insert(t1.value7.Options, {
				type = "Section",
				Name = v656,
				func = t34
			})

            function t34.Visible(_, p155)
                if p155 == nil then
                    v658.Visible = not v658.Visible

                    return
                end

                v658.Visible = p155
            end
            function t34.Destroy(_)
                v658:Destroy()
            end
            function t34.Set(_, p158)
                if p158 then
                    v674.Text = t1.value27(p158)
                end
            end

            return t34
        end
        function t33.AddSectionColorToggle(_, p160)
            local v679 = p160[1]
            if not v679 then
                v679 = p160.Name

                if not v679 then
                    v679 = p160.Title or "Cor das Sections"
                end
            end
            local Desc = p160.Desc
            if not Desc then
                Desc = p160.Description or ""
            end
            local Callback = t1.value16:GetCallback(p160, 3)
            local v682 = p160[4] or (p160.Flag or false)
            local u683 = p160[2] or (p160.Default or false)
            if type(v682) == "string" and t1.value11[v682] ~= nil then
                u683 = t1.value19(v682)
            end
            local Colors = p160.Colors
            if not Colors then
                Colors = p160[5]

                if not Colors then
                    Colors = {
						Color3.fromRGB(90, 10, 10),
						Color3.fromRGB(15, 15, 15)
					}
                end
            end
            local u685 = Colors
            if type(u685) ~= "table" or #u685 < 2 then
                u685 = {
					Color3.fromRGB(90, 10, 10),
					Color3.fromRGB(15, 15, 15)
				}
            elseif #u685 > 5 then
                local t35 = {}

                for i = 1, 5 do
                    t35[i] = u685[i]
                end

                u685 = t35
            end
            local v688 = tonumber(p160.Speed) or 2
            local v689, v690 = t1.value36(v607, v679, Desc, UDim2.new(1, -38), "Toggle")
            local v691 = v689
            local v692 = v690
            local value13_15 = t1.value13
            local value15_34 = t1.value15
            local uDim2_54 = UDim2.new(0, 35, 0, 18)
            local uDim2_55 = UDim2.new(1, -10, 0.5)
            local vector2_19 = Vector2.new(1, 0.5)
            local v698 = t1.value32["Color Stroke"]
            local v699 = value13_15(value15_34("Frame", v691, {
				Size = uDim2_54,
				Position = uDim2_55,
				AnchorPoint = vector2_19,
				BackgroundColor3 = v698
			}), "Stroke")
            t1.value33("Corner", v699, UDim.new(0.5, 0))
            local value15_35 = t1.value15
            local uDim2_56 = UDim2.new(0.8, 0, 0.8, 0)
            local uDim2_57 = UDim2.new(0.5, 0, 0.5, 0)
            local vector2_20 = Vector2.new(0.5, 0.5)
            local v704 = value15_35("Frame", v699, {
				BackgroundTransparency = 1,
				Size = uDim2_56,
				Position = uDim2_57,
				AnchorPoint = vector2_20
			})
      local value13_16 = t1.value13
            local value15_36 = t1.value15
            local uDim2_58 = UDim2.new(0, 12, 0, 12)
            local uDim2_59 = UDim2.new(0, 0, 0.5)
            local vector2_21 = Vector2.new(0, 0.5)
            local v710 = t1.value32["Color Theme"]
            local v711 = value13_16(value15_36("Frame", v704, {
				Size = uDim2_58,
				Position = uDim2_59,
				AnchorPoint = vector2_21,
				BackgroundColor3 = v710
			}), "Theme")
            local value33 = t1.value33
            local t36 = { UDim.new(0.5, 0) }
            value33("Corner", v711, v2(t36))
            local u714 = false
            local function v715()
            end
            local function v717()
                if u714 then
                    return
                end

                u714 = true
                task.spawn(function()
                    local n3 = 1

                    while u714 do
                        n3 = n3 % #u685 + 1
                        local v1881 = u685[n3]
                        for v1884, v1885 in ipairs(t12.value54) do

                            t1.value29({
								v1885.Label,
								"TextColor3",
								v1881,
								v688
							})
                        end
                        for _, v in ipairs(t12.value53) do
                            t1.value29({
								v,
								"BackgroundColor3",
								v1881,
								v688
							})
                        end
                        task.wait(v688)
                    end
                end)
            end
            local function u718()

                for v1368, v1369 in ipairs(t12.value54) do

                    t1.value29({
						v1369.Label,
						"TextColor3",
						t1.value32["Color Text"],
						0.35
					})
                end
                for _, v in ipairs(t12.value53) do
                    t1.value29({
						v,
						"BackgroundColor3",
						t1.value32["Color Theme"],
						0.35
					})
                end
            end
            local u716
            local function v719(p161)
                if u716 then
                    return
                end

                u683 = p161
                t1.value20(v682, u683)
                t1.value16:FireCallback(Callback, u683)

                if u683 then
                    t1.value29({
						v711,
						"Position",
						UDim2.new(1, 0, 0.5),
						0.25
					})
                    t1.value29({
						v711,
						"BackgroundTransparency",
						0,
						0.25
					})
                    t1.value29({
						v711,
						"AnchorPoint",
						Vector2.new(1, 0.5),
						0.25,
						false
					})
                    v717()
                else
                    t1.value29({
						v711,
						"Position",
						UDim2.new(0, 0, 0.5),
						0.25
					})
                    t1.value29({
						v711,
						"BackgroundTransparency",
						0.8,
						0.25
					})
                    t1.value29({
						v711,
						"AnchorPoint",
						Vector2.new(0, 0.5),
						0.25,
						false
					})
                    v715()
                    u718()
                end

                u716 = false
            end
            task.spawn(v719, u683)
            v691.Activated:Connect(function()
                v719(not u683)
            end)
            local t37 = {
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v691, ...)
            end,
				Destroy = function(_)
                v715()
                v691:Destroy()
            end,
				Callback = function(_, ...)
                t1.value16:InsertCallback(Callback, ...)()
            end,
				Set = function(_, p166, p167)
                local v1379 = type(p166) == "string"

                if v1379 then
                    v1379 = type(p167) == "string"
                end

                if v1379 then
                    v692:SetTitle(p166)
                    v692:SetDesc(p167)

                    return
                end

                if type(p166) == "string" then
                    v692:SetTitle(p166)

                    return
                end

                if type(p166) == "boolean" then
                    if u716 and p167 then

                        repeat
                            task.wait()
                        until not u716
                    end

                    task.spawn(v719, p166)

                    return
                end

                if type(p166) == "table" and #p166 >= 2 then
                    if #p166 > 5 then
                        for i = 1, 5 do
                            ({})[i] = p166[i]
                        end

                        return
                    end
                elseif type(p166) ~= "function" then
                end
            end
			}
            if v682 then
                table.insert(t1.value7.Options, {
					type = "Toggle",
					Name = v679,
					Flag = v682,
					Default = false,
					func = t37
				})
            end

            return t37
        end
        function t33.AddParagraph(_, p169)
            local v723 = p169[1]

            if not v723 then
                v723 = p169.Title or "Paragraph"
            end

            local v724 = p169[2]

            if not v724 then
                v724 = p169.Text or ""
            end

            local v725, v726 = t1.value36(v607, v723, v724, UDim2.new(1, -20), "Paragraph")
            local v727 = v725
            local v728 = v726

            return {
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v727, ...)
            end,
				Destroy = function(_)
                v727:Destroy()
            end,
				SetTitle = function(_, p173)
                local v1386 = v728
                local t38 = { t1.value27(p173) }

                v1386:SetTitle(v2(t38))
            end,
				SetDesc = function(_, p175)
                v728:SetDesc(t1.value27(p175))
            end,
				Set = function(_, p177, p178)
                if p177 and p178 then
                    v728:SetTitle(t1.value27(p177))
                    v728:SetDesc(t1.value27(p178))

                    return
                end

                if p177 then
                    local v1393 = v728
                    local t39 = { t1.value27(p177) }

                    v1393:SetDesc(v2(t39))
                end
            end
			}
        end
        function t33.AddButton(_, p180)
            local v731 = p180[1]

            if not v731 then
                v731 = p180.Name

                if not v731 then
                    v731 = p180.Title or "Button!"
                end
            end

            local Desc = p180.Desc

            if not Desc then
                Desc = p180.Description or ""
            end

            local Callback = t1.value16:GetCallback(p180, 2)
            local v734, v735 = t1.value36(v607, v731, Desc, UDim2.new(1, -20), "Button")
            local v736 = v734
            local v737 = v735
            local value15_37 = t1.value15
            local uDim2_60 = UDim2.new(0, 14, 0, 14)
            local uDim2_61 = UDim2.new(1, -10, 0.5)
            local vector2_22 = Vector2.new(1, 0.5)

            value15_37("ImageLabel", v736, {
				Size = uDim2_60,
				Position = uDim2_61,
				AnchorPoint = vector2_22,
				BackgroundTransparency = 1,
				Image = "rbxassetid://10709791437"
			})
            v736.Activated:Connect(function()
                t1.value16:FireCallback(Callback)
            end)

            return {
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v736, ...)
            end,
				Destroy = function(_)
                v736:Destroy()
            end,
				Callback = function(_, ...)
                t1.value16:InsertCallback(Callback, ...)
            end,
				Set = function(_, p185, p186)
                local v1401 = type(p185) == "string"

                if v1401 then
                    v1401 = type(p186) == "string"
                end

                if v1401 then
                    v737:SetTitle(p185)
                    v737:SetDesc(p186)

                    return
                end

                if type(p185) == "string" then
                    v737:SetTitle(p185)

                    return
                end

                if type(p185) ~= "function" then
                end
            end
			}
        end
        function t33.AddToggle(_, p188)
            local v744 = p188[1]
            if not v744 then
                v744 = p188.Name

                if not v744 then
                    v744 = p188.Title or "Toggle"
                end
            end
            local Desc = p188.Desc
            if not Desc then
                Desc = p188.Description or ""
            end
            local Callback = t1.value16:GetCallback(p188, 3)
            local v747 = p188[4] or (p188.Flag or false)
            local u748 = p188[2] or (p188.Default or false)
            if type(v747) == "string" and t1.value11[v747] ~= nil then
                u748 = t1.value19(v747)
            end
            local v749, v750 = t1.value36(v607, v744, Desc, UDim2.new(1, -38), "Toggle")
            local v751 = v749
            local v752 = v750
            local value13_17 = t1.value13
            local value15_38 = t1.value15
            local uDim2_62 = UDim2.new(0, 35, 0, 18)
            local uDim2_63 = UDim2.new(1, -10, 0.5)
            local vector2_23 = Vector2.new(1, 0.5)
            local v758 = t1.value32["Color Stroke"]
            local v759 = value13_17(value15_38("Frame", v751, {
				Size = uDim2_62,
				Position = uDim2_63,
				AnchorPoint = vector2_23,
				BackgroundColor3 = v758
			}), "Stroke")
      t1.value33("Corner", v759, UDim.new(0.5, 0))
            local value15_39 = t1.value15
            local uDim2_64 = UDim2.new(0.8, 0, 0.8, 0)
            local uDim2_65 = UDim2.new(0.5, 0, 0.5, 0)
            local vector2_24 = Vector2.new(0.5, 0.5)
            local v764 = value15_39("Frame", v759, {
				BackgroundTransparency = 1,
				Size = uDim2_64,
				Position = uDim2_65,
				AnchorPoint = vector2_24
			})
            local value13_18 = t1.value13
            local value15_40 = t1.value15
            local uDim2_66 = UDim2.new(0, 12, 0, 12)
            local uDim2_67 = UDim2.new(0, 0, 0.5)
            local vector2_25 = Vector2.new(0, 0.5)
            local v770 = t1.value32["Color Theme"]
            local v771 = value13_18(value15_40("Frame", v764, {
				Size = uDim2_66,
				Position = uDim2_67,
				AnchorPoint = vector2_25,
				BackgroundColor3 = v770
			}), "Theme")
            t1.value33("Corner", v771, UDim.new(0.5, 0))
            local u772
            local function v773(p189)
                if u772 then
                    return
                end

                u748 = p189
                t1.value20(v747, u748)
                t1.value16:FireCallback(Callback, u748)

                if u748 then
                    t1.value29({
						v771,
						"Position",
						UDim2.new(1, 0, 0.5),
						0.25
					})
                    t1.value29({
						v771,
						"BackgroundTransparency",
						0,
						0.25
					})
                    t1.value29({
						v771,
						"AnchorPoint",
						Vector2.new(1, 0.5),
						0.25,
						false
					})
                else
                    t1.value29({
						v771,
						"Position",
						UDim2.new(0, 0, 0.5),
						0.25
					})
                    t1.value29({
						v771,
						"BackgroundTransparency",
						0.8,
						0.25
					})
                    t1.value29({
						v771,
						"AnchorPoint",
						Vector2.new(0, 0.5),
						0.25,
						false
					})
                end

                u772 = false
            end
            task.spawn(v773, u748)
            v751.Activated:Connect(function()
                v773(not u748)
            end)
            local t40 = {
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v751, ...)
            end,
				Destroy = function(_)
                v751:Destroy()
            end,
				Callback = function(_, ...)
                t1.value16:InsertCallback(Callback, ...)()
            end,
				Set = function(_, p194, p195)
                local v1409 = type(p194) == "string"

                if v1409 then
                    v1409 = type(p195) == "string"
                end

                if v1409 then
                    v752:SetTitle(p194)
                    v752:SetDesc(p195)

                    return
                end

                if type(p194) == "string" then
                    v752:SetTitle(p194)

                    return
                end

                if type(p194) == "boolean" then
                    if u772 and p195 then

                        repeat
                            task.wait()
                        until not u772
                    end

                    task.spawn(v773, p194)

                    return
                end

                if type(p194) ~= "function" then
                end
            end
			}
            if v747 then
                table.insert(t1.value7.Options, {
					type = "Toggle",
					Name = v744,
					Flag = v747,
					Default = false,
					func = t40
				})
            end

            return t40
        end
        function t33.AddDropdown(_, p197)
            local v777 = p197[1]
            if not v777 then
                v777 = p197.Name

                if not v777 then
                    v777 = p197.Title or "Dropdown"
                end
            end
            local Desc = p197.Desc
            if not Desc then
                Desc = p197.Description or ""
            end
            local v779 = p197[2]
            if not v779 then
                v779 = p197.Options or {}
            end
            local v780 = p197[3]
            if not v780 then
                v780 = p197.Default or {}
            end
            local v781 = p197[5] or (p197.Flag or false)
            local v782 = p197.MultiSelect or false
            local Callback = t1.value16:GetCallback(p197, 4)
            local v784, _ = t1.value36(v607, v777, Desc, UDim2.new(1, -180))
            local v786 = v784
            local value13_19 = t1.value13
            local value15_41 = t1.value15
            local uDim2_68 = UDim2.new(0, 150, 0, 20)
            local uDim2_69 = UDim2.new(1, -10, 0.5)
            local vector2_26 = Vector2.new(1, 0.5)
            local v792 = t1.value32["Color Stroke"]
            local v793 = value13_19(value15_41("Frame", v786, {
				Size = uDim2_68,
				Position = uDim2_69,
				AnchorPoint = vector2_26,
				BackgroundColor3 = v792
			}), "Stroke")
            t1.value33("Corner", v793, UDim.new(0, 4))
            local value13_20 = t1.value13
            local value15_42 = t1.value15
            local uDim2_70 = UDim2.new(1, -26, 0.8, 0)
            local vector2_27 = Vector2.new(0, 0.5)
            local uDim2_71 = UDim2.new(0, 10, 0.5, 0)
            local GothamBold = Enum.Font.GothamBold
            local AtEnd = Enum.TextTruncate.AtEnd
            local v801 = t1.value32["Color Text"]
            local v802 = value13_20(value15_42("TextLabel", v793, {
				Size = uDim2_70,
				AnchorPoint = vector2_27,
				Position = uDim2_71,
				BackgroundTransparency = 1,
				Font = GothamBold,
				TextSize = 14.4,
				TextTruncate = AtEnd,
				TextXAlignment = "Left",
				TextColor3 = v801,
				Text = "..."
			}), "Text")
            table.insert(t1.value35.Dropdown, {
				Title = v802,
				Label = v802
			})
            local value15_43 = t1.value15
            local uDim2_72 = UDim2.new(0, 13, 0, 13)
            local uDim2_73 = UDim2.new(1, -8, 0.5)
            local vector2_28 = Vector2.new(1, 0.5)
            local v807 = value15_43("ImageLabel", v793, {
				Size = uDim2_72,
				Position = uDim2_73,
				AnchorPoint = vector2_28,
				Image = "rbxassetid://10709791523",
				BackgroundTransparency = 1
			})
      v793.MouseEnter:Connect(function()
                t1.value29({
					v793,
					"BackgroundColor3",
					t1.value32["Color Stroke"]:Lerp(t1.value32["Color Theme"], 0.3),
					0.15
				})
            end)
            v793.MouseLeave:Connect(function()
                t1.value29({
					v793,
					"BackgroundColor3",
					t1.value32["Color Stroke"],
					0.2
				})
            end)
            local value15_44 = t1.value15
            local value13_21 = t12.value13
            local uDim2_74 = UDim2.new(1, 0, 1, 0)
            local v811 = value15_44("TextButton", value13_21, {
				Name = "AntiClick",
				Size = uDim2_74,
				BackgroundTransparency = 1,
				Visible = false,
				Text = ""
			})
            local value15_45 = t1.value15
            local uDim2_75 = UDim2.fromOffset(152, 0)
            local color3_40 = Color3.fromRGB(255, 255, 255)
            local vector2_29 = Vector2.new(0, 1)
            local v816 = value15_45("Frame", v811, {
				Size = uDim2_75,
				BackgroundTransparency = 0.04,
				BackgroundColor3 = color3_40,
				AnchorPoint = vector2_29,
				Name = "DropdownFrame",
				ClipsDescendants = true,
				Active = true
			})
            t1.value33("Corner", v816)
            t1.value33("Stroke", v816)
            t1.value33("Gradient", v816, {
				Rotation = 60
			})
            t1.value33("Shadow", v816, {
				Spread = 16,
				Transparency = 0.62
			})
            local value13_22 = t1.value13
            local value15_46 = t1.value15
            local v819 = t1.value32["Color Theme"]
            local uDim2_76 = UDim2.new(1, 0, 1, -6)
            local uDim2_77 = UDim2.new(0, 0, 0, 6)
            local uDim2_78 = UDim2.new()
            local t41 = {
				ScrollBarImageColor3 = v819,
				Size = uDim2_76,
				Position = uDim2_77,
				ScrollBarThickness = 2,
				BackgroundTransparency = 1,
				BorderSizePixel = 0,
				CanvasSize = uDim2_78,
				ScrollingDirection = "Y",
				AutomaticCanvasSize = "Y",
				Active = true
			}
            local value15_47 = t1.value15
            local uDim12 = UDim.new(0, 8)
            local uDim13 = UDim.new(0, 8)
            local uDim14 = UDim.new(0, 6)
            local uDim15 = UDim.new(0, 6)
            local v829 = value13_22(value15_46("ScrollingFrame", v816, t41, {
				value15_47("UIPadding", {
					PaddingLeft = uDim12,
					PaddingRight = uDim13,
					PaddingTop = uDim14,
					PaddingBottom = uDim15
				}),
				t1.value15("UIListLayout", {
					Padding = UDim.new(0, 6)
				})
			}), "ScrollBar")
            local n4 = 5
            local u831
            local t42 = {}
            local function v833()
                t1.value29({
					v807,
					"Rotation",
					0,
					0.25
				})
                t1.value29({
					v816,
					"Size",
					UDim2.new(0, 152, 0, 0),
					0.25
				})
                t1.value29({
					v807,
					"ImageColor3",
					Color3.fromRGB(255, 255, 255),
					0.25
				})
                v807.Image = "rbxassetid://10709791523"
                v811.Visible = false
                u831 = false
            end
            local function v834()
                local n5 = 0
                local n6 = 0

                for _, child in pairs(v829:GetChildren()) do
                    if child:IsA("TextButton") and child.Visible then
                        n5 += 1

                        if n5 <= 10 then
                            n6 += child.Size.Y.Offset
                        end
                    end
                end

                n4 = n6 + math.max(math.clamp(n5, 0, 10) - 1, 0) * 6 + 12

                if v811.Visible then
                    t1.value29({
						v816,
						"Size",
						UDim2.fromOffset(152, n4),
						0.2
					})
                end
            end
            local function v835()
                local AbsolutePosition = v793.AbsolutePosition
                local AbsoluteSize = t1.value22.AbsoluteSize
                local v1417 = math.clamp(AbsolutePosition.X / t1.value9, 0, AbsoluteSize.X / t1.value9 - v816.Size.X.Offset)
                local v1418 = math.clamp(AbsolutePosition.Y / t1.value9, 0, AbsoluteSize.Y / t1.value9)
                local uDim2_79 = UDim2.fromOffset(v1417, v1418)
                local v1420 = if not (AbsolutePosition.Y > AbsoluteSize.Y / 1.4) then not (n4 > 80) and 0 or 0.5 else 1

                v816.AnchorPoint = Vector2.new(0, v1420)
                t1.value29({
					v816,
					"Position",
					uDim2_79,
					0.1
				})
            end
            local u836
            local u837
            local v838 = type(v780) ~= "table" and { v780 } or v780
            local v839 = v782 and {}
            if not v839 then
                v839 = type(v781) == "string" and t1.value11[v781] ~= nil and t1.value19(v781) or v838[1]
            end
            local u840 = v839
            if v782 then
                for k, v in pairs(type(v781) == "string" and t1.value11[v781] ~= nil and t1.value19(v781) or v838) do
                    local v843 = k
                    local v844 = type(v843) == "string"

                    if v844 then
                        v844 = v779[v843]

                        if not v844 then
                            v844 = table.find(v779, v843)
                        end
                    end

                    if v844 then
                        u840[v843] = v
                    elseif v779[v] then
                        u840[v] = true
                    end
                end
            end
            local function u845()
                if v782 then
                    local t43 = {}

                    for k, v in pairs(u840) do
                        if v then
                            table.insert(t43, k)
                        end
                    end

                    local v1424 = v802
                    local v1425 = #t43 > 0

                    if v1425 then
                        v1425 = table.concat(t43, ", ")
                    end

                    v1424.Text = v1425 or "..."

                    return
                end

                v802.Text = tostring(u840 or "...")
            end
            local function u846()
                if v782 then
                    for _, v in pairs(t42) do
                        local nodes = v.nodes
                        local Stats = v.Stats

                        t1.value29({
							nodes[2],
							"BackgroundTransparency",
							not Stats and 0.8 or 0,
							0.35
						})

                        local value29 = t1.value29
                        local v1431 = nodes[2]
                        local v1432 = Stats

                        if Stats then
                            v1432 = UDim2.fromOffset(4, 12)
                        end

                        if not v1432 then
                            v1432 = UDim2.fromOffset(4, 4)
                        end

                        value29({
							v1431,
							"Size",
							v1432,
							0.35
						})
                        t1.value29({
							nodes[3],
							"TextTransparency",
							not Stats and 0.4 or 0,
							0.35
						})
                    end
                else
                    for _, v in pairs(t42) do
                        local v1435 = v.Value == u840
                        local nodes = v.nodes

                        t1.value29({
							nodes[2],
							"BackgroundTransparency",
							not v1435 and 1 or 0,
							0.35
						})

                        local value29 = t1.value29
                        local v1438 = nodes[2]
                        local v1439 = v1435

                        if v1435 then
                            v1439 = UDim2.fromOffset(4, 14)
                        end

                        if not v1439 then
                            v1439 = UDim2.fromOffset(4, 4)
                        end

                        value29({
							v1438,
							"Size",
							v1439,
							0.35
						})
                        t1.value29({
							nodes[3],
							"TextTransparency",
							not v1435 and 0.4 or 0,
							0.35
						})
                    end
                end

                u845()
            end
            local function v847(p198)
                if v782 then
                    p198.Stats = not p198.Stats
                    u840[p198.Name] = p198.Stats
                    t1.value20(v781, v782 and u840 or tostring(u840))
                    t1.value16:FireCallback(Callback, u840)
                else
                    u840 = p198.Value
                    t1.value20(v781, v782 and u840 or tostring(u840))
                    t1.value16:FireCallback(Callback, u840)
                end

                u846()
            end
            function u836(p199, p200)
                local str = tostring(type(p199) == "string" and p199 or p200)

                if t42[str] then
                    return
                end

                local v1453 = typeof(p200) == "Instance" and (p200:IsA("Player") and p200)

                if not v1453 then
                    v1453 = t1.value5:FindFirstChild(str)
                end

                local v1454 = v1453
                local t44 = {
					index = p199,
					Value = p200,
					Name = str,
					Stats = false,
					LastCB = 0
				}

                if v782 then
                    local v1456 = u840[str]

                    u840[str] = v1456 or false
                    t44.Stats = v1456
                end

                local value33 = t1.value33
                local v1458 = v829
                local uDim2_80 = UDim2.new(1, 0, 0, not v1454 and 26 or 32)
                local uDim2_81 = UDim2.new(0, 0, 0.5)
                local vector2_30 = Vector2.new(0, 0.5)
                local v1462 = value33("Button", v1458, {
					Name = "Option",
					Size = uDim2_80,
					Position = uDim2_81,
					AnchorPoint = vector2_30
				})

                t1.value33("Corner", v1462, UDim.new(0, 4))

                local value13_23 = t1.value13
                local value15_48 = t1.value15
                local uDim2_82 = UDim2.new(0, 2, 0.5)
                local uDim2_83 = UDim2.new(0, 4, 0, 4)
                local v1467 = t1.value32["Color Theme"]
                local vector2_31 = Vector2.new(0, 0.5)
                local v1469 = value13_23(value15_48("Frame", v1462, {
					Position = uDim2_82,
					Size = uDim2_83,
					BackgroundColor3 = v1467,
					BackgroundTransparency = 1,
					AnchorPoint = vector2_31
				}), "Theme")

                t1.value33("Corner", v1469, UDim.new(0.5, 0))

                local n7 = 12

                if v1454 then
                    local value15_49 = t1.value15
                    local uDim2_84 = UDim2.fromOffset(22, 22)
                    local uDim2_85 = UDim2.new(0, 10, 0.5)
                    local vector2_32 = Vector2.new(0, 0.5)
                    local v1475 = t1.value32["Color Stroke"]
                    local v1476 = value15_49("Frame", v1462, {
						Size = uDim2_84,
						Position = uDim2_85,
						AnchorPoint = vector2_32,
						BackgroundColor3 = v1475,
						BackgroundTransparency = 0
					})

                    t1.value33("Corner", v1476, UDim.new(1, 0))
                    t1.value33("Stroke", v1476)

                    local value15_50 = t1.value15
                    local uDim2_86 = UDim2.new(1, 0, 1, 0)
                    local Icon2 = t1.value7:GetIcon("user")
                    local v1480 = t1.value32["Color Dark Text"]
                    local Crop = Enum.ScaleType.Crop
                    local v1482 = value15_50("ImageLabel", v1476, {
						Size = uDim2_86,
						BackgroundTransparency = 1,
						Image = Icon2,
						ImageColor3 = v1480,
						ScaleType = Crop
					})

          t1.value33("Corner", v1482, UDim.new(1, 0))
                    task.spawn(function()
                        local ok, result = pcall(function()
                            return t1.value5:GetUserThumbnailAsync(v1454.UserId, Enum.ThumbnailType.HeadShot, Enum.ThumbnailSize.Size48x48)
                        end)

                        if ok then
                            ok = v1482.Parent
                        end

                        if ok then
                            v1482.ImageColor3 = Color3.fromRGB(255, 255, 255)
                            v1482.ImageTransparency = 1
                            v1482.Image = result
                            t1.value29({
								v1482,
								"ImageTransparency",
								0,
								0.2
							})
                        end
                    end)
                    n7 = 40
                end

                local value13_24 = t1.value13
                local value15_51 = t1.value15
                local uDim2_87 = UDim2.new(1, -(n7 + 8), 1, 0)
                local uDim2_88 = UDim2.new(0, n7, 0, 0)
                local v1487 = t1.value32["Color Text"]
                local GothamBold3 = Enum.Font.GothamBold
                local AtEnd2 = Enum.TextTruncate.AtEnd
                local v1490 = value13_24(value15_51("TextLabel", v1462, {
					Size = uDim2_87,
					Position = uDim2_88,
					Text = str,
					TextColor3 = v1487,
					Font = GothamBold3,
					TextXAlignment = "Left",
					TextTruncate = AtEnd2,
					BackgroundTransparency = 1,
					TextTransparency = 0.4
				}), "Text")

                v1462.Activated:Connect(function()
                    local v1890 = t42[str]

                    v847(v1890)
                end)
                t44.nodes = {
					v1462,
					v1469,
					v1490
				}
                t42[str] = t44
            end
            function u837(p201, p202)
                local str = tostring(type(p201) == "string" and p201 or p202)

                if t42[str] then
                    if v782 then
                        u840[str] = nil
                    else
                        u840 = nil
                    end

                    t42[str].nodes[1]:Destroy()
                    table.clear(t42[str])
                    t42[str] = nil
                end
            end
            local function v848(p203, p204)
                if p204 then
                    for _, v in pairs(t42) do
                        u837(v.index, v.Value)
                    end
                end

                for k, v in pairs(p203) do
                    u836(k, v)
                end

                t1.value20(v781, v782 and u840 or tostring(u840))
                t1.value16:FireCallback(Callback, u840)
                u846()
            end
            for k, v in pairs(v779) do
                u836(k, v)
            end
            t1.value20(v781, v782 and u840 or tostring(u840))
            t1.value16:FireCallback(Callback, u840)
            u846()
            v786.Activated:Connect(function()
                if u831 then
                    return
                end

                if v811.Visible then
                    v807.Image = "rbxassetid://10709791523"
                    t1.value29({
						v807,
						"ImageColor3",
						Color3.fromRGB(255, 255, 255),
						0.25
					})
                    t1.value29({
						v816,
						"Size",
						UDim2.new(0, 152, 0, 0),
						0.25
					})
                    v811.Visible = false

                    return
                end

                v811.Visible = true
                v807.Image = "rbxassetid://10709790948"
                t1.value29({
					v807,
					"ImageColor3",
					t1.value32["Color Theme"],
					0.25
				})
                t1.value29({
					v816,
					"Size",
					UDim2.fromOffset(152, n4),
					0.3
				})
            end)
            v811.MouseButton1Down:Connect(v833)
            v811.MouseButton1Click:Connect(v833)
            t12.value1:GetPropertyChangedSignal("Visible"):Connect(v833)
            v793:GetPropertyChangedSignal("AbsolutePosition"):Connect(v835)
            v786.Activated:Connect(v834)
            v829.ChildAdded:Connect(v834)
            v829.ChildRemoved:Connect(v834)
            v835()
            v834()

            return {
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v786, ...)
            end,
				Destroy = function(_)
                v786:Destroy()
            end,
				Callback = function(_, ...)
                t1.value16:InsertCallback(Callback, ...)(u840)
            end,
				Add = function(_, ...)
                local t45 = { ... }

                if type(t45[1]) == "table" then
                    for _, v in ipairs(t45) do
                        u836(v, v)
                    end

                    return
                end

                for _, v in ipairs(t45) do
                    u836(v, v)
                end
            end,
				Remove = function(_, p210)
                for k, v in pairs(t42) do
                    local v1504 = k

                    if type(p210) == "number" and v1504 == p210 or p210 == v.Name then
                        u837(v1504, v.Value)
                    end
                end
            end,
				Select = function(_, p212)
                for _, v in pairs(t42) do
                    if v.Name == tostring(p212) then
                        Select(v)
                    end
                end
            end,
				Set = function(_, p214, p215)
                if type(p214) == "table" then
                    v848(p214, not p215)

                    return
                end

                if type(p214) ~= "function" then
                end
            end
			}
        end
        function t33.AddBackgroundSelector(_, p217)
            local v853 = p217[1]

            if not v853 then
                v853 = p217.Name

                if not v853 then
                    v853 = p217.Title or "Imagem de Fundo"
                end
            end

            local Desc = p217.Desc

            if not Desc then
                Desc = p217.Description or ""
            end

            local v855 = p217.Images or {}
            local v856 = p217.Default or "Nenhuma"
            local t46 = {}
            local v858 = p217.Callback or function()
            end

            for _, v in ipairs(v855) do
                table.insert(t46, v.Name)
            end

            return (t33:AddDropdown({
				Name = v853,
				Desc = Desc,
				Options = t46,
				Default = v856,
				Callback = function(p218)
                local s1 = ""
                local v1514, v1515, v1516 = ipairs(v855)
                local g1518
                local v1517
                repeat
                    v1516, v1517 = v1514(v1515, v1516)

                    if not v1516 then
                        g1518 = true
                    end

                    if g1518 then
                        break
                    end
                until p218 == v1517.Name
                if not g1518 then
                    s1 = v1517.AssetId
                end
                if s1 == "" then
                    t12.value1.Image = ""
                    t12.value1.ImageTransparency = 1

                    for _, v in pairs(t1.value7.Instances) do
                        local v1521 = v.Type == "Gradient"

                        if v1521 then
                            v1521 = v.Instance.Parent == t12.value1
                        end

                        if v1521 then
                            v.Instance.Enabled = true
                        end
                    end
                else
                    t12.value1.Image = s1
                    t12.value1.ImageTransparency = 0.2
                    t12.value1.ScaleType = Enum.ScaleType.Crop

                    for _, v in pairs(t1.value7.Instances) do
                        local v1524 = v.Type == "Gradient"

                        if v1524 then
                            v1524 = v.Instance.Parent == t12.value1
                        end

                        if v1524 then
                            v.Instance.Enabled = false
                        end
                    end
                end
                v858(p218, s1)
            end
			}))
        end
        function t33.AddSlider(_, p220)
            local v863 = p220[1]

            if not v863 then
                v863 = p220.Name

                if not v863 then
                    v863 = p220.Title or "Slider!"
                end
            end

            local Desc = p220.Desc

            if not Desc then
                Desc = p220.Description or ""
            end

            local v865 = p220[2]

            if not v865 then
                v865 = p220.MinValue or (p220.Min or 10)
            end

            local v866 = p220[3]

            if not v866 then
                v866 = p220.MaxValue or (p220.Max or 100)
            end

            local v867 = p220[4] or (p220.Increase or 1)
            local Callback = t1.value16:GetCallback(p220, 6)
            local v869 = p220[7] or (p220.Flag or false)
            local u870 = p220[5] or (p220.Default or 25)

            if type(v869) == "string" and t1.value11[v869] ~= nil then
                u870 = t1.value19(v869)
            end

            local v871 = v865 / v867
            local v872 = v866 / v867
            local u873 = v871
            local u874 = v872
            local v875, v876 = t1.value36(v607, v863, Desc, UDim2.new(1, -180))
            local v877 = v875
            local v878 = v876
            local value15_52 = t1.value15
            local uDim2_89 = UDim2.new(0.45, 0, 1)
            local uDim2_90 = UDim2.new(1)
            local vector2_33 = Vector2.new(1, 0)
            local v883 = value15_52("TextButton", v877, {
				Size = uDim2_89,
				Position = uDim2_90,
				AnchorPoint = vector2_33,
				AutoButtonColor = false,
				Text = "",
				BackgroundTransparency = 1
			})
            local value13_25 = t1.value13
            local value15_53 = t1.value15
            local v886 = t1.value32["Color Stroke"]
            local uDim2_91 = UDim2.new(1, -20, 0, 7)
            local uDim2_92 = UDim2.new(0.5, 0, 0.5)
            local vector2_34 = Vector2.new(0.5, 0.5)
            local v890 = value13_25(value15_53("Frame", v883, {
				BackgroundColor3 = v886,
				Size = uDim2_91,
				Position = uDim2_92,
				AnchorPoint = vector2_34
			}), "Stroke")

            t1.value33("Corner", v890)

            local value13_26 = t1.value13
            local value15_54 = t1.value15
            local v893 = t1.value32["Color Theme"]
            local uDim2_93 = UDim2.fromScale(0.3, 1)
            local v895 = value13_26(value15_54("Frame", v890, {
				BackgroundColor3 = v893,
				Size = uDim2_93,
				BorderSizePixel = 0
			}), "Theme")

            t1.value33("Corner", v895)

            local value15_55 = t1.value15
            local uDim2_94 = UDim2.new(0, 7, 0, 14)
            local color3_41 = Color3.fromRGB(230, 230, 230)
            local uDim2_95 = UDim2.fromScale(0.3, 0.5)
            local vector2_35 = Vector2.new(0.5, 0.5)
            local v901 = value15_55("Frame", v890, {
				Size = uDim2_94,
				BackgroundColor3 = color3_41,
				Position = uDim2_95,
				AnchorPoint = vector2_35,
				BackgroundTransparency = 0.1
			})

            t1.value33("Corner", v901)

            local value13_27 = t1.value13
            local value15_56 = t1.value15
            local uDim2_96 = UDim2.new(0, 14, 0, 14)
            local vector2_36 = Vector2.new(1, 0.5)
            local uDim2_97 = UDim2.new(0, 0, 0.5)
            local v907 = t1.value32["Color Text"]
            local FredokaOne = Enum.Font.FredokaOne
            local v909 = t1.value34.Slider or 12
            local v910 = value13_27(value15_56("TextLabel", v883, {
				Size = uDim2_96,
				AnchorPoint = vector2_36,
				Position = uDim2_97,
				BackgroundTransparency = 1,
				TextColor3 = v907,
				Font = FredokaOne,
				TextSize = v909
			}), "Text")


      table.insert(t1.value35.Slider, {
				Label = v910,
				Title = v910
			})

            local v911 = t1.value15("UIScale", v910)
            local v912 = t1.value15("Frame", v890, {
				Position = UDim2.new(0, 0, 0.5, 0),
				Visible = false
			})

            local function v913(p221)
                local v1526 = math.floor(tonumber(p221 * v867) * 100) / 100
                local v1527 = v910
                local str = tostring(v1526)

                u870 = v1526
                v1527.Text = str
                t1.value16:FireCallback(Callback, u870)
            end
            local function v914()
                local X = t1.value6:GetMouse().X
                local AbsolutePositionX = v912.AbsolutePosition.X
                local v1532 = (X - AbsolutePositionX) / v890.AbsoluteSize.X
                v901.Position = UDim2.new(math.clamp(v1532, 0, 1), 0, 0.5, 0)
            end
            local function v915()
                v895.Size = UDim2.new(v901.Position.X.Scale, 0, 1, 0)

                local XScale = v901.Position.X.Scale
                local floor = math.floor
                local v1535 = u874 - u873
                local v1536 = floor(XScale * u874 / u874 * v1535 + u873)

                v913(v1536)
            end

            v883.MouseButton1Down:Connect(function()
                t1.value29({
					v901,
					"Transparency",
					0,
					0.3
				})
                v607.ScrollingEnabled = false

                while t1.value1:IsMouseButtonPressed(Enum.UserInputType.MouseButton1) do
                    task.wait()
                    v914()
                end

                t1.value29({
					v901,
					"Transparency",
					0.2,
					0.3
				})
                v607.ScrollingEnabled = true
                t1.value20(v869, u870)
            end)
            v910:GetPropertyChangedSignal("Text"):Connect(function()
                v911.Scale = 0.3
                t1.value29({
					v911,
					"Scale",
					1.2,
					0.1
				})
                t1.value29({
					v910,
					"Rotation",
					math.random(-1, 1) * 5,
					0.15,
					true
				})
                t1.value29({
					v911,
					"Scale",
					1,
					0.2
				})
                t1.value29({
					v910,
					"Rotation",
					0,
					0.1
				})
            end)

            function SetSlider(p222)
                if type(p222) ~= "number" then
                    return
                end

                local v1538 = (p222 - u873) / (u874 - u873)

                t1.value20(v869, p222)
                t1.value29({
					v901,
					"Position",
					UDim2.fromScale(math.clamp(v1538, 0, 1), 0.5),
					0.3,
					true
				})
            end

            SetSlider(u870)
            v901:GetPropertyChangedSignal("Position"):Connect(v915)
            v915()

            local t47 = {
				Set = function(_, p224, p225)
                if p224 and p225 then
                    v878:SetTitle(p224)
                    v878:SetDesc(p225)

                    return
                end

                if type(p224) == "string" then
                    v878:SetTitle(p224)

                    return
                end

                if type(p224) == "function" then
                    Callback = p224

                    return
                end

                if type(p224) == "number" then
                    SetSlider(p224)
                end
            end,
				Callback = function(_, ...)
                t1.value16:InsertCallback(Callback, ...)((tonumber(u870)))
            end,
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v877, ...)
            end,
				Destroy = function(_)
                v877:Destroy()
            end
			}

            if v869 then
                local insert = table.insert
                local Options = t1.value7.Options
                local v919 = p220[5]

                if not v919 then
                    v919 = p220.Default or u873
                end

                local v920 = u873

                insert(Options, {
					type = "Slider",
					Name = v863,
					Flag = v869,
					Default = v919,
					Min = v920,
					func = t47
				})
            end

            return t47
        end
        function t33.AddColorPicker(_, p230)
            local t48 = {}
            local t49 = {}
            local v925 = p230[1]

            if not v925 then
                t48.value1 = p230.Name
                v925 = t48.value1

                if not t48.value1 then
                    v925 = p230.Title or "Cor personalizada"
                end
            end

            local Desc = p230.Desc

            if not Desc then
                Desc = p230.Description or ""
            end

            t49.value1 = t1.value16:GetCallback(p230, 3)
            t49.value2 = p230[4] or (p230.Flag or false)
            t49.value3 = p230.MaxRecent or 8

            local DisplayMode = p230.DisplayMode

            if not DisplayMode then
                DisplayMode = p230.Display or "Hex"
            end

            local v928 = tostring(DisplayMode):lower():gsub("%s+", "")
            local v929 = v928:find("hex", 1, true) ~= nil
            local v930 = v928:find("rgb", 1, true) ~= nil

            if not v929 and not v930 then
                v929 = true
            end

            local function v931(p231)
                if typeof(p231) ~= "string" then
                    return nil
                end

                local v1551 = p231:gsub("#", ""):gsub("%s", "")

                if #v1551 == 3 then
                    v1551 = v1551:sub(1, 1):rep(2) .. v1551:sub(2, 2):rep(2) .. v1551:sub(3, 3):rep(2)
                end

                if #v1551 ~= 6 then
                    return nil
                end

                local num = tonumber(v1551:sub(1, 2), 16)
                local sub = v1551.sub
                local num2 = tonumber(sub(v1551, 3, 4), 16)
                local num3 = tonumber(v1551:sub(5, 6), 16)

                if not num or (not num2 or not num3) then
                    return nil
                end

                return Color3.fromRGB(num, num2, num3)
            end

            function t49.value4(p232)
                return string.format("#%02X%02X%02X", math.floor(p232.R * 255 + 0.5), math.floor(p232.G * 255 + 0.5), (math.floor(p232.B * 255 + 0.5)))
            end
            function t49.value5(p233)
                return string.format("%d, %d, %d", math.floor(p233.R * 255 + 0.5), math.floor(p233.G * 255 + 0.5), (math.floor(p233.B * 255 + 0.5)))
            end
            function t49.value6(p234)
                if typeof(p234) ~= "string" then
                    return nil
                end

                local t50 = {}
                local v1558, v1559, v1560 = p234:gmatch("%d+")

                repeat
                    v1560 = v1558(v1559, v1560)

                    if not v1560 then
                        break
                    end

                    table.insert(t50, (tonumber(v1560)))
                until #t50 >= 3

                if #t50 < 3 then
                    return nil
                end

                return Color3.fromRGB(math.clamp(t50[1], 0, 255), math.clamp(t50[2], 0, 255), math.clamp(t50[3], 0, 255))
            end
            function t49.value7(p235)
                if typeof(p235) ~= "string" then
                    return nil
                end

                local ok, result = pcall(BrickColor.new, p235)

                if ok then
                    ok = result

                    if result then
                        ok = typeof(result) == "BrickColor"

                        if ok then
                            ok = tostring(result.Name):lower() == p235:lower()
                        end
                    end
                end

                if ok then
                    return result.Color, result.Name
                end

                return nil
            end
            function t49.value8(p236)
                local ok, result = pcall(BrickColor.new, p236)

                if ok and result then
                    return result.Name
                end

                return nil
            end

            local v932 = p230[2]

            if not v932 then
                v932 = p230.Default or "#137D81"
            end

            local v933, v934 = (function(p237)
                if typeof(p237) == "Color3" then
                    return p237, "Color3"
                end

                if typeof(p237) == "BrickColor" then
                    return p237.Color, "BrickColor"
                end

                if type(p237) == "string" then
                    local v1565 = v931(p237)

                    if v1565 then
                        return v1565, "Color3"
                    end

                    local v1566 = t49.value7(p237)

                    if v1566 then
                        return v1566, "BrickColorName"
                    end
                end

                return nil, nil
            end)(v932)

            t48.value2 = v933

            local value2 = t48.value2

            if not t48.value2 then
                value2 = Color3.fromRGB(19, 125, 129)
            end

            t48.value2 = value2

            local value2_2 = t49.value2

            if type(value2_2) == "string" and t1.value11[value2_2] ~= nil then
                local v937 = v931(t1.value19(t49.value2))

                if v937 then
                    t48.value2 = v937
                end
            end

            local ReturnFormat = p230.ReturnFormat

            if not ReturnFormat then
                t48.value3 = p230.Format
                ReturnFormat = t48.value3

                if not t48.value3 then
                    t48.value4 = p230.OutputFormat
                    t48.value3 = t48.value4

                    if not t48.value4 then
                        t48.value3 = v934 or "Color3"
                    end

                    ReturnFormat = t48.value3
                end
            end

            local v939 = tostring(ReturnFormat):lower():gsub("%s+", "")

            t49.value9 = "Color3"

            local v940 = v939:find("brickcolorname", 1, true)

            if not v940 then
                t48.value5 = v939 == "name"
                v940 = t48.value5

                if not t48.value5 then
                    v940 = v939:find("nomedabrickcolor", 1, true) or v939:find("nomedacor", 1, true)
                end
            end

            if v940 then
                t49.value9 = "BrickColorName"
            else
                t48.value3 = v939:find("brickcolor", 1, true)

                if t48.value3 then
                    t49.value9 = "BrickColor"
                end
            end

            function t48.value4(p238)
                if t49.value9 == "BrickColor" then
                    local ok, result = pcall(BrickColor.new, p238)

                    if ok and result then
                        return result, t49.value4(p238)
                    end
                elseif t49.value9 == "BrickColorName" then
                    local v1570 = t49.value8(p238)

                    if v1570 then
                        return v1570, t49.value4(p238)
                    end
                end

                return p238, t49.value4(p238)
            end

            t49.value10 = t48.value4

            local v941, v942, v943 = t48.value2:ToHSV()

            t48.value4 = v941
            t48.value5 = v942
            t48.value6 = v943
            t49.value11 = t48.value4
            t49.value12 = t48.value5
            t49.value13 = t48.value6

            if t49.value12 <= 0 then
                t49.value12 = 1
            end

            local Presets = p230.Presets

            if not Presets then
                t48.value8 = Color3.fromRGB(108, 99, 255)
                t48.value9 = Color3.fromRGB(33, 150, 243)
                t48.value10 = Color3.fromRGB(67, 181, 129)
                t48.value11 = Color3.fromRGB(255, 193, 7)
                t48.value12 = Color3.fromRGB(255, 107, 107)
                t48.value13 = Color3.fromRGB(233, 30, 140)
                t48.value14 = Color3.fromRGB(156, 106, 222)
                t48.value7 = Color3.fromRGB
                Presets = {
					t48.value8,
					t48.value9,
					t48.value10,
					t48.value11,
					t48.value12,
					t48.value13,
					t48.value14,
					t48.value7(255, 255, 255)
				}
            end

            t48.value9 = v929 and v930
            t48.value7 = t48.value9

            if t48.value9 then
                t48.value7 = UDim2.new(1, -300)
            end

            local value7 = t48.value7

            if not t48.value7 then
                value7 = UDim2.new(1, -230)
            end

            local v946, v947 = t1.value36(v607, v925, Desc, value7, "ColorPicker")

            t48.value7 = v946
            t48.value8 = v947
            t49.value14 = t48.value7
            t49.value15 = t48.value8
            t48.value8 = t1.value15
            t48.value10 = "Frame"
            t48.value11 = t49.value14
            t48.value13 = "Size"

            local uDim2_98 = UDim2.new(0, 0, 0, 20)
            local AutomaticSizeX = Enum.AutomaticSize.X
            local uDim2_99 = UDim2.new(1, -10, 0.5)
            local vector2_37 = Vector2.new(1, 0.5)

            t48.value12 = {
				[v2361] = uDim2_98,
				AutomaticSize = AutomaticSizeX,
				Position = uDim2_99,
				AnchorPoint = vector2_37,
				BackgroundTransparency = 1
			}
            t48.value14 = t1.value15

            local uDim16 = UDim.new(0, 8)
            local t51 = {
				FillDirection = "Horizontal",
				VerticalAlignment = "Center",
				HorizontalAlignment = "Right",
				SortOrder = "LayoutOrder",
				Padding = uDim16
			}

            t48.value9 = t48.value8(t48.value10, t48.value11, t48.value12, { t48.value14("UIListLayout", t51) })
            t49.value16 = nil
            t49.value17 = nil

            if v929 then
                t48.value10 = t1.value13
                t48.value13 = t1.value15

                local uDim2_100 = UDim2.new(0, 96, 1, 0)
                local v955 = t1.value32["Color Stroke"]

                t48.value12 = t48.value10(t48.value13("Frame", t48.value9, {
					Size = uDim2_100,
					BackgroundColor3 = v955,
					LayoutOrder = 1
				}), "Stroke")
                t1.value33("Corner", t48.value12, UDim.new(0, 5))
                t48.value10 = t1.value13
                t48.value14 = t1.value15

                local uDim2_101 = UDim2.new(1, -10, 1, 0)
                local uDim2_102 = UDim2.new(0, 5, 0, 0)
                local GothamBold = Enum.Font.GothamBold
                local v959 = t1.value34.ColorPicker or 10
                local v960 = t1.value32["Color Text"]
                local v961 = t49.value4(t48.value2)

                t49.value16 = t48.value10(t48.value14("TextBox", t48.value12, {
					Size = uDim2_101,
					Position = uDim2_102,
					BackgroundTransparency = 1,
					Font = GothamBold,
					TextSize = v959,
					TextColor3 = v960,
					TextXAlignment = "Left",
					ClearTextOnFocus = false,
					Text = v961
				}), "Text")
                t48.value10 = table.insert

                local ColorPicker = t1.value35.ColorPicker
                local value16 = t49.value16
                local value16_2 = t49.value16

                t48.value10(ColorPicker, {
					Label = value16,
					Title = value16_2
				})
            end

            if v930 then
                t48.value10 = t1.value13
                t48.value14 = t1.value15

                local uDim2_103 = UDim2.new(0, 104, 1, 0)
                local v966 = t1.value32["Color Stroke"]

                t48.value12 = t48.value10(t48.value14("Frame", t48.value9, {
					Size = uDim2_103,
					BackgroundColor3 = v966,
					LayoutOrder = 2
				}), "Stroke")
                t1.value33("Corner", t48.value12, UDim.new(0, 5))
                t48.value10 = t1.value13

                local value15_57 = t1.value15
                local uDim2_104 = UDim2.new(1, -10, 1, 0)
                local uDim2_105 = UDim2.new(0, 5, 0, 0)
                local GothamBold = Enum.Font.GothamBold
                local v971 = t1.value34.ColorPicker or 10
                local v972 = t1.value32["Color Text"]

                t49.value17 = t48.value10(value15_57("TextBox", t48.value12, {
					Size = uDim2_104,
					Position = uDim2_105,
					BackgroundTransparency = 1,
					Font = GothamBold,
					TextSize = v971,
					TextColor3 = v972,
					TextXAlignment = "Left",
					ClearTextOnFocus = false,
					Text = "..."
				}), "Text")
                t48.value10 = table.insert

                local ColorPicker = t1.value35.ColorPicker
                local value17 = t49.value17
                local value17_2 = t49.value17

                t48.value10(ColorPicker, {
					Label = value17,
					Title = value17_2
				})
            end

            t48.value10 = t1.value15

            local uDim2_106 = UDim2.new(0, 50, 1, 0)

            t48.value12 = t48.value10("TextButton", t48.value9, {
				Size = uDim2_106,
				BackgroundTransparency = 1,
				AutoButtonColor = false,
				Text = "",
				LayoutOrder = 3
			})
            t48.value10 = t1.value15

            local uDim2_107 = UDim2.new(0, 20, 0, 20)
            local uDim2_108 = UDim2.new(0, 0, 0.5)
            local vector2_38 = Vector2.new(0, 0.5)

            t49.value18 = t48.value10("Frame", t48.value12, {
				Size = uDim2_107,
				Position = uDim2_108,
				AnchorPoint = vector2_38,
				BackgroundColor3 = t48.value2
			})
            t1.value33("Corner", t49.value18, UDim.new(0, 5))
            t1.value33("Stroke", t49.value18)

            local value15_58 = t1.value15
            local uDim2_109 = UDim2.new(0, 16, 0, 16)
            local uDim2_110 = UDim2.new(1, 0, 0.5)
            local vector2_39 = Vector2.new(1, 0.5)
            local chevrondown = t1.value7.Icons.chevrondown
            local v985 = t1.value32["Color Text"]

            t49.value19 = value15_58("ImageLabel", t48.value12, {
				Size = uDim2_109,
				Position = uDim2_110,
				AnchorPoint = vector2_39,
				BackgroundTransparency = 1,
				Image = chevrondown,
				ImageColor3 = v985
			})

            local value13_28 = t1.value13
            local value15_59 = t1.value15
            local v988 = v607
            local uDim2_111 = UDim2.new(1, 0, 0, 0)
            local v990 = t1.value32["Color Stroke"]

            t49.value20 = value13_28(value15_59("Frame", v988, {
				Size = uDim2_111,
				BackgroundColor3 = v990,
				ClipsDescendants = true,
				Name = "Option"
			}), "Stroke")
            t1.value33("Corner", t49.value20, UDim.new(0, 6))

            local value15_60 = t1.value15
            local value20 = t49.value20
            local t52 = {
				Size = UDim2.new(1, 0, 0, 0),
				AutomaticSize = "Y",
				BackgroundTransparency = 1
			}
            local value15_61 = t1.value15
            local uDim17 = UDim.new(0, 10)
            local v996 = value15_61("UIListLayout", {
				SortOrder = "LayoutOrder",
				Padding = uDim17
			})
            local value15_62 = t1.value15
            local uDim18 = UDim.new(0, 12)
            local uDim19 = UDim.new(0, 12)
            local uDim20 = UDim.new(0, 12)
            local uDim21 = UDim.new(0, 28)

            t49.value21 = value15_60("Frame", value20, t52, {
				v996,
				value15_62("UIPadding", {
					PaddingLeft = uDim18,
					PaddingRight = uDim19,
					PaddingTop = uDim20,
					PaddingBottom = uDim21
				})
			})

            local value13_29 = t1.value13
            local value15_63 = t1.value15
            local value21 = t49.value21
            local uDim2_112 = UDim2.new(1, 0, 0, 12)
            local GothamMedium4 = Enum.Font.GothamMedium
            local v1007 = t1.value32["Color Dark Text"]

            value13_29(value15_63("TextLabel", value21, {
				Size = uDim2_112,
				BackgroundTransparency = 1,
				Font = GothamMedium4,
				TextColor3 = v1007,
				TextSize = 10,
				TextXAlignment = "Left",
				Text = "Recentes",
				LayoutOrder = 0
			}), "DarkText")

            local value15_64 = t1.value15
            local value21_2 = t49.value21
            local t53 = {
				Size = UDim2.new(1, 0, 0, 22),
				BackgroundTransparency = 1,
				LayoutOrder = 1
			}
            local value15_65 = t1.value15
            local uDim22 = UDim.new(0, 8)

            t49.value22 = value15_64("Frame", value21_2, t53, { value15_65("UIListLayout", {
				FillDirection = "Horizontal",
				Padding = uDim22
			}) })

            local value13_30 = t1.value13
            local value15_66 = t1.value15
            local value21_3 = t49.value21
            local uDim2_113 = UDim2.new(1, 0, 0, 12)
            local GothamMedium5 = Enum.Font.GothamMedium
            local v1018 = t1.value32["Color Dark Text"]

            value13_30(value15_66("TextLabel", value21_3, {
				Size = uDim2_113,
				BackgroundTransparency = 1,
				Font = GothamMedium5,
				TextColor3 = v1018,
				TextSize = 10,
				TextXAlignment = "Left",
				Text = "Matiz",
				LayoutOrder = 2
			}), "DarkText")

            local v1019 = t1.value15("TextButton", t49.value21, {
				Size = UDim2.new(1, 0, 0, 16),
				BackgroundTransparency = 1,
				AutoButtonColor = false,
				Text = "",
				LayoutOrder = 3
			})
            local value15_67 = t1.value15
            local uDim2_114 = UDim2.new(1, 0, 1, 0)
            local color3_42 = Color3.fromRGB(255, 255, 255)
            local v1023 = value15_67("Frame", v1019, {
				Size = uDim2_114,
				BorderSizePixel = 0,
				BackgroundColor3 = color3_42
			}, { t1.value15("UIGradient", {
				Color = ColorSequence.new({
					ColorSequenceKeypoint.new(0, Color3.fromHSV(0, 1, 1)),
					ColorSequenceKeypoint.new(0.16666666666667, Color3.fromHSV(0.16666666666667, 1, 1)),
					ColorSequenceKeypoint.new(0.33333333333333, Color3.fromHSV(0.33333333333333, 1, 1)),
					ColorSequenceKeypoint.new(0.5, Color3.fromHSV(0.5, 1, 1)),
					ColorSequenceKeypoint.new(0.66666666666667, Color3.fromHSV(0.66666666666667, 1, 1)),
					ColorSequenceKeypoint.new(0.83333333333333, Color3.fromHSV(0.83333333333333, 1, 1)),
					ColorSequenceKeypoint.new(1, Color3.fromHSV(1, 1, 1))
				})
			}) })

            t1.value33("Corner", v1023, UDim.new(0.5, 0))

            local value15_68 = t1.value15
            local uDim2_115 = UDim2.new(0, 7, 0, 22)
            local uDim2_116 = UDim2.new(t49.value11, 0, 0.5)
            local vector2_40 = Vector2.new(0.5, 0.5)
            local color3_43 = Color3.fromRGB(230, 230, 230)

            t49.value23 = value15_68("Frame", v1023, {
				Size = uDim2_115,
				Position = uDim2_116,
				AnchorPoint = vector2_40,
				BackgroundColor3 = color3_43,
				BackgroundTransparency = 0.1,
				ZIndex = 2
			})
            t1.value33("Corner", t49.value23)

            local value13_31 = t1.value13
            local value15_69 = t1.value15
            local value21_4 = t49.value21
            local uDim2_117 = UDim2.new(1, 0, 0, 12)
            local GothamMedium6 = Enum.Font.GothamMedium
            local v1034 = t1.value32["Color Dark Text"]

            value13_31(value15_69("TextLabel", value21_4, {
				Size = uDim2_117,
				BackgroundTransparency = 1,
				Font = GothamMedium6,
				TextColor3 = v1034,
				TextSize = 10,
				TextXAlignment = "Left",
				Text = "Brilho",
				LayoutOrder = 4
			}), "DarkText")

            local v1035 = t1.value15("TextButton", t49.value21, {
				Size = UDim2.new(1, 0, 0, 16),
				BackgroundTransparency = 1,
				AutoButtonColor = false,
				Text = "",
				LayoutOrder = 5
			})
            local value15_70 = t1.value15
            local uDim2_118 = UDim2.new(1, 0, 1, 0)
            local color3_44 = Color3.fromRGB(0, 0, 0)
            local v1039 = value15_70("Frame", v1035, {
				Size = uDim2_118,
				BorderSizePixel = 0,
				BackgroundColor3 = color3_44
			}, { t1.value15("UIGradient", {
				Color = ColorSequence.new({
					ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 0, 0)),
					ColorSequenceKeypoint.new(1, Color3.fromHSV(t49.value11, 1, 1))
				})
			}) })

            t1.value33("Corner", v1039, UDim.new(0.5, 0))
            t49.value24 = v1039.UIGradient

            local value15_71 = t1.value15
            local uDim2_119 = UDim2.new(0, 7, 0, 22)
            local uDim2_120 = UDim2.new(t49.value13, 0, 0.5)
            local vector2_41 = Vector2.new(0.5, 0.5)
            local color3_45 = Color3.fromRGB(230, 230, 230)

            t49.value25 = value15_71("Frame", v1039, {
				Size = uDim2_119,
				Position = uDim2_120,
				AnchorPoint = vector2_41,
				BackgroundColor3 = color3_45,
				BackgroundTransparency = 0.1,
				ZIndex = 2
			})
            t1.value33("Corner", t49.value25)
            t49.value26 = false
            t49.value27 = {}

            for i, v in ipairs(Presets) do
                if i > t49.value3 then
                    break
                end

                table.insert(t49.value27, v)
            end

            t49.value28 = t48.value2

            function t49.value29(p239, p240, p241)
                local value15_72 = t1.value15

                if not p241 then
                    p241 = UDim2.new(0, 22, 0, 22)
                end

                local v1575 = value15_72("TextButton", p239, {
					Size = p241,
					BackgroundColor3 = p240,
					AutoButtonColor = false,
					Text = ""
				})

                t1.value33("Corner", v1575, UDim.new(0, 5))
                t1.value33("Stroke", v1575)

                return v1575
            end

            t49.value30 = nil
            t49.value31 = nil

            function t49.value31()

                for v1578, v1579 in pairs(t49.value22:GetChildren()) do

                    if v1579:IsA("TextButton") then
                        v1579:Destroy()
                    end
                end
                for _, v in ipairs(t49.value27) do
                    local v1582 = v

                    t49.value29(t49.value22, v1582).Activated:Connect(function()
                        t49.value30(v1582, true, true)
                    end)
                end
            end
            function t49.value32(p242)
                local v1584 = t49.value4(p242)

                for i = #t49.value27, 1, -1 do
                    local v1586 = i

                    if v1584 == t49.value4(t49.value27[v1586]) then
                        table.remove(t49.value27, v1586)
                    end
                end

                table.insert(t49.value27, 1, p242)

                while #t49.value27 > t49.value3 do
                    table.remove(t49.value27, #t49.value27)
                end

                t49.value31()
            end
            function t49.value30(p243, p244, p245)
                local ToHSV = p243.ToHSV

                t49.value28 = p243

                local v1591, v1592, v1593 = ToHSV(p243)

                t49.value11 = v1591
                t49.value13 = v1593
                t49.value12 = v1592 > 0 and v1592 or 1
                t49.value18.BackgroundColor3 = p243

                if t49.value16 and not t49.value16:IsFocused() then
                    t49.value16.Text = t49.value4(p243)
                end

                if t49.value17 and not t49.value17:IsFocused() then
                    t49.value17.Text = t49.value5(p243)
                end

                t49.value23.Position = UDim2.new(t49.value11, 0, 0.5)
                t49.value25.Position = UDim2.new(t49.value13, 0, 0.5)
                t49.value24.Color = ColorSequence.new({
					ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 0, 0)),
					ColorSequenceKeypoint.new(1, Color3.fromHSV(t49.value11, 1, 1))
				})
                t1.value20(t49.value2, t49.value4(p243))

                if p244 then
                    local v1594, v1595 = t49.value10(p243)

                    t1.value16:FireCallback(t49.value1, v1594, v1595)
                end

                if p245 then
                    t49.value32(p243)
                end
            end

            t49.value33 = t49.value21:FindFirstChildOfClass("UIListLayout")
            t49.value34 = t49.value21:FindFirstChildOfClass("UIPadding")

            function t49.value35()
                local AbsoluteSizeY = t49.value21.AbsoluteSize.Y

                if t49.value33 then
                    local AbsoluteContentSizeY = t49.value33.AbsoluteContentSize.Y

                    if t49.value34 then
                        AbsoluteContentSizeY = AbsoluteContentSizeY + t49.value34.PaddingTop.Offset + t49.value34.PaddingBottom.Offset
                    end

                    AbsoluteSizeY = math.max(AbsoluteSizeY, AbsoluteContentSizeY)
                end

                return AbsoluteSizeY + 12
            end

            local function v1047(p246)
                t49.value26 = p246 ~= nil and p246 or not t49.value26

                if t49.value26 then
                    t1.value29({
						t49.value19,
						"Rotation",
						180,
						0.25
					})
                    t1.value29({
						t49.value20,
						"Size",
						UDim2.new(1, 0, 0, t49.value35()),
						0.25
					})
                    task.spawn(function()
                        for _ = 1, 20 do
                            t1.value4.Heartbeat:Wait()

                            if not t49.value26 then
                                return
                            end

                            local v1892 = t49.value35()

                            if math.abs(t49.value20.Size.Y.Offset - v1892) > 0.5 then
                                t49.value20.Size = UDim2.new(1, 0, 0, v1892)
                            end
                        end
                    end)

                    return
                end

                t1.value29({
					t49.value19,
					"Rotation",
					0,
					0.25
				})
        t1.value29({
					t49.value20,
					"Size",
					UDim2.new(1, 0, 0, 0),
					0.25
				})
            end
            local function v1048()
                if t49.value26 then
                    t49.value20.Size = UDim2.new(1, 0, 0, t49.value35())
                end
            end

            t48.value12.Activated:Connect(function()
                v1047()
            end)

            if t49.value33 then
                t49.value33:GetPropertyChangedSignal("AbsoluteContentSize"):Connect(v1048)
            end

            t49.value21:GetPropertyChangedSignal("AbsoluteSize"):Connect(v1048)
            t49.value31()

            local v1049 = v1023
            local value23 = t49.value23

            local function v1051(p247)
                t49.value11 = p247
                t49.value30(Color3.fromHSV(t49.value11, 1, t49.value13), true, false)
            end

            v1019.MouseButton1Down:Connect(function()
                v607.ScrollingEnabled = false
                t1.value29({
					value23,
					"Size",
					UDim2.new(0, 9, 0, 24),
					0.15
				})

                while t1.value1:IsMouseButtonPressed(Enum.UserInputType.MouseButton1) do
                    task.wait()

                    local v1604 = t1.value6:GetMouse().X - v1049.AbsolutePosition.X
                    local v1605 = math.clamp(v1604 / v1049.AbsoluteSize.X, 0, 1)

                    value23.Position = UDim2.new(v1605, 0, 0.5)
                    v1051(v1605)
                end

                t1.value29({
					value23,
					"Size",
					UDim2.new(0, 7, 0, 22),
					0.15
				})
                v607.ScrollingEnabled = true
                t49.value30(t49.value28, true, true)
            end)

            local v1052 = v1039
            local value25 = t49.value25

            local function v1054(p248)
                t49.value13 = p248
                t49.value30(Color3.fromHSV(t49.value11, 1, t49.value13), true, false)
            end

            v1035.MouseButton1Down:Connect(function()
                v607.ScrollingEnabled = false
                t1.value29({
					value25,
					"Size",
					UDim2.new(0, 9, 0, 24),
					0.15
				})

                while t1.value1:IsMouseButtonPressed(Enum.UserInputType.MouseButton1) do
                    task.wait()

                    local v1607 = t1.value6:GetMouse().X - v1052.AbsolutePosition.X
                    local v1608 = math.clamp(v1607 / v1052.AbsoluteSize.X, 0, 1)

                    value25.Position = UDim2.new(v1608, 0, 0.5)
                    v1054(v1608)
                end

                t1.value29({
					value25,
					"Size",
					UDim2.new(0, 7, 0, 22),
					0.15
				})
                v607.ScrollingEnabled = true
                t49.value30(t49.value28, true, true)
            end)

            if t49.value16 then
                t49.value16.FocusLost:Connect(function(_)
                    local v1610 = v931(t49.value16.Text)

                    if v1610 then
                        t49.value30(v1610, true, true)

                        return
                    end

                    t49.value16.Text = t49.value4(t49.value28)
                end)
            end

            if t49.value17 then
                t49.value17.FocusLost:Connect(function(_)
                    local v1612 = t49.value6(t49.value17.Text)

                    if v1612 then
                        t49.value30(v1612, true, true)

                        return
                    end

                    t49.value17.Text = t49.value5(t49.value28)
                end)
            end

            t49.value30(t48.value2, false, false)
            task.spawn(function()
                task.wait()

                if t49.value26 then
                    t49.value20.Size = UDim2.new(1, 0, 0, t49.value35())
                end
            end)

            local t54 = {
				Set = function(_, p252, p253)
                local v1616 = type(p252) == "string"

                if v1616 then
                    v1616 = type(p253) == "string"
                end

                if v1616 then
                    t49.value15:SetTitle(p252)
                    t49.value15:SetDesc(p253)

                    return
                end

                if type(p252) == "string" and v931(p252) then
                    t49.value30(v931(p252), true, false)

                    return
                end

                if type(p252) == "string" and t49.value7(p252) then
                    t49.value30(t49.value7(p252), true, false)

                    return
                end

                if type(p252) == "string" then
                    t49.value15:SetTitle(p252)

                    return
                end

                if typeof(p252) == "Color3" then
                    t49.value30(p252, true, false)

                    return
                end

                if typeof(p252) == "BrickColor" then
                    t49.value30(p252.Color, true, false)

                    return
                end

                if type(p252) == "function" then
                    t49.value1 = p252
                end
            end,
				Get = function(_)
                return t49.value10(t49.value28)
            end,
				Callback = function(_, ...)
                local v1619, v1620 = t49.value10(t49.value28)

                t1.value16:InsertCallback(t49.value1, ...)(v1619, v1620)
            end,
				Visible = function(_, ...)
                t1.value16:ToggleVisible(t49.value14, ...)
                t1.value16:ToggleVisible(t49.value20, ...)
            end,
				Expand = function(_, p258)
                v1047(p258)
            end,
				Destroy = function(_)
                t49.value14:Destroy()
                t49.value20:Destroy()
            end
			}

            if t49.value2 then
                local insert = table.insert

                t48.value15 = t1.value7.Options
                t48.value16 = t49.value2
                t48.value17 = t49.value4(t48.value2)
                insert(t48.value15, {
					type = "ColorPicker",
					Name = v925,
					Flag = t48.value16,
					Default = t48.value17,
					func = t54
				})
            end

            return t54
        end
        function t33.AddTextBox(_, p261)
            local v1059 = p261[1]

            if not v1059 then
                v1059 = p261.Name

                if not v1059 then
                    v1059 = p261.Title or "Text Box"
                end
            end

            local Desc = p261.Desc

            if not Desc then
                Desc = p261.Description or ""
            end

            local v1061 = p261[2]

            if not v1061 then
                v1061 = p261.Default or ""
            end

            local v1062 = p261[5]

            if not v1062 then
                v1062 = p261.PlaceholderText or "Input"
            end

            local v1063 = p261[3] or (p261.ClearText or false)
            local Callback = t1.value16:GetCallback(p261, 4)
            local v1065 = type(v1061) ~= "string"

            if not v1065 then
                v1065 = v1061:gsub(" ", ""):len() < 1
            end

            if not v1065 then
            end

            local v1066, _ = t1.value36(v607, v1059, Desc, UDim2.new(1, -38))
            local v1068 = v1066
            local value13_32 = t1.value13
            local value15_73 = t1.value15
            local uDim2_121 = UDim2.new(0, 150, 0, 18)
            local uDim2_122 = UDim2.new(1, -10, 0.5)
            local vector2_42 = Vector2.new(1, 0.5)
            local v1074 = t1.value32["Color Stroke"]
            local v1075 = value13_32(value15_73("Frame", v1068, {
				Size = uDim2_121,
				Position = uDim2_122,
				AnchorPoint = vector2_42,
				BackgroundColor3 = v1074
			}), "Stroke")

            t1.value33("Corner", v1075, UDim.new(0, 4))

            local value15_74 = t1.value15
            local uDim2_123 = UDim2.new(0.85, 0, 0.85, 0)
            local vector2_43 = Vector2.new(0.5, 0.5)
            local uDim2_124 = UDim2.new(0.5, 0, 0.5, 0)
            local v1080 = value15_74("Frame", v1075, {
				Size = uDim2_123,
				AnchorPoint = vector2_43,
				Position = uDim2_124,
				BackgroundTransparency = 1,
				Active = true,
				ZIndex = 1
			})

            v1080.InputBegan:Connect(function(input)
                local v1626 = input.UserInputType == Enum.UserInputType.MouseButton1

                if not v1626 then
                    v1626 = input.UserInputType == Enum.UserInputType.Touch
                end

                if v1626 then
                    input:StopPropagation()
                end
            end)

            local value13_33 = t1.value13
            local value15_75 = t1.value15
            local uDim2_125 = UDim2.new(1, 0, 1, 0)
            local vector2_44 = Vector2.new(0.5, 0.5)
            local uDim2_126 = UDim2.new(0.5, 0, 0.5, 0)
            local GothamBold = Enum.Font.GothamBold
            local v1087 = t1.value32["Color Text"]
            local v1088 = value13_33(value15_75("TextBox", v1080, {
				Size = uDim2_125,
				AnchorPoint = vector2_44,
				Position = uDim2_126,
				BackgroundTransparency = 1,
				Font = GothamBold,
				TextScaled = true,
				TextColor3 = v1087,
				ClearTextOnFocus = v1063,
				PlaceholderText = v1062,
				Text = ""
			}), "Text")

            table.insert(t1.value35.TextBox, {
				Label = v1088,
				Title = v1088
			})

            local value15_76 = t1.value15
            local uDim2_127 = UDim2.new(0, 12, 0, 12)
            local uDim2_128 = UDim2.new(0, -5, 0.5)
            local vector2_45 = Vector2.new(1, 0.5)
            local v1093 = value15_76("ImageLabel", v1075, {
				Size = uDim2_127,
				Position = uDim2_128,
				AnchorPoint = vector2_45,
				Image = "rbxassetid://15637081879",
				BackgroundTransparency = 1
			})

            v1088.InputBegan:Connect(function(input)
                local v1628 = input.UserInputType == Enum.UserInputType.MouseButton1

                if not v1628 then
                    v1628 = input.UserInputType == Enum.UserInputType.Touch
                end

                if v1628 then
                    input:StopPropagation()
                end
            end)

            local t55 = {}

            local function v1095()
                local Text = v1088.Text

                if Text:gsub(" ", ""):len() > 0 then
                    if t55.OnChanging then
                        Text = t55.OnChanging(Text) or Text
                    end

                    t1.value16:FireCallback(Callback, Text)
                    v1088.Text = Text
                end
            end

            v1088.FocusLost:Connect(v1095)
            v1095()
            v1088.FocusLost:Connect(function()
                t1.value29({
					v1093,
					"ImageColor3",
					Color3.fromRGB(255, 255, 255),
					0.2
				})
            end)
            v1088.Focused:Connect(function()
                t1.value29({
					v1093,
					"ImageColor3",
					t1.value32["Color Theme"],
					0.2
				})
            end)
            t55.OnChanging = false

            function t55.Visible(_, ...)
                t1.value16:ToggleVisible(v1068, ...)
            end
            function t55.Destroy(_)
                v1068:Destroy()
            end

            return t55
        end
        function t33.AddTextBox2(_, p265)
            local v1098 = p265[1]
            if not v1098 then
                v1098 = p265.Name

                if not v1098 then
                    v1098 = p265.Title or "Text Box"
                end
            end
            local Desc = p265.Desc
            if not Desc then
                Desc = p265.Description or ""
            end
            local v1100 = p265[2]
            if not v1100 then
                v1100 = p265.Default or ""
            end
            local v1101 = p265[5]
            if not v1101 then
                v1101 = p265.PlaceholderText or "Input"
            end
            local v1102 = p265[3] or (p265.ClearText or false)
            local Callback = t1.value16:GetCallback(p265, 4)
            local v1104 = type(v1100) ~= "string"
            if not v1104 then
                v1104 = v1100:gsub(" ", ""):len() < 1
            end
            if v1104 then
                v1100 = false
            end
            local n8 = 18
            local n9 = 150
            if type(p265.Size) == "table" then
                local v1107 = p265.Size[1]

                if not v1107 then
                    v1107 = p265.Size.Width or n9
                end

                n9 = v1107

                local v1108 = p265.Size[2]

                if not v1108 then
                    v1108 = p265.Size.Height or n8
                end

                n8 = v1108
            end
            local v1109 = tonumber(p265.Width) or n9
            local v1110 = tonumber(p265.Height) or n8
            local v1111 = math.clamp(v1109, 60, 600)
            local v1112 = math.clamp(v1110, 18, 200)
            local v1113, _ = t1.value36(v607, v1098, Desc, UDim2.new(1, -(v1111 + 40)))
            local v1115 = v1113
            local value13_34 = t1.value13
            local value15_77 = t1.value15
            local uDim2_129 = UDim2.new(0, v1111, 0, v1112)
            local uDim2_130 = UDim2.new(1, -10, 0.5)
            local vector2_46 = Vector2.new(1, 0.5)
            local v1121 = t1.value32["Color Stroke"]
            local v1122 = value13_34(value15_77("Frame", v1115, {
				Size = uDim2_129,
				Position = uDim2_130,
				AnchorPoint = vector2_46,
				BackgroundColor3 = v1121
			}), "Stroke")
            t1.value33("Corner", v1122, UDim.new(0, 4))
            local value15_78 = t1.value15
            local uDim2_131 = UDim2.new(0.9, 0, 0.85, 0)
            local vector2_47 = Vector2.new(0.5, 0.5)
            local uDim2_132 = UDim2.new(0.5, 0, 0.5, 0)
            local v1127 = value15_78("Frame", v1122, {
				Size = uDim2_131,
				AnchorPoint = vector2_47,
				Position = uDim2_132,
				BackgroundTransparency = 1,
				Active = true,
				ZIndex = 1
			})
            v1127.InputBegan:Connect(function(input)
                local v1633 = input.UserInputType == Enum.UserInputType.MouseButton1

                if not v1633 then
                    v1633 = input.UserInputType == Enum.UserInputType.Touch
                end

                if v1633 then
                    input:StopPropagation()
                end
            end)
            local value13_35 = t1.value13
            local value15_79 = t1.value15
            local uDim2_133 = UDim2.new(1, 0, 1, 0)
            local vector2_48 = Vector2.new(0.5, 0.5)
            local uDim2_134 = UDim2.new(0.5, 0, 0.5, 0)
            local GothamBold = Enum.Font.GothamBold
            local v1134 = v1112 > 24
            local v1135 = t1.value32["Color Text"]
            local v1136 = value13_35(value15_79("TextBox", v1127, {
				Size = uDim2_133,
				AnchorPoint = vector2_48,
				Position = uDim2_134,
				BackgroundTransparency = 1,
				Font = GothamBold,
				TextScaled = true,
				TextWrapped = v1134,
				TextColor3 = v1135,
				ClearTextOnFocus = v1102,
				PlaceholderText = v1101,
				Text = ""
			}), "Text")
            table.insert(t1.value35.TextBox, {
				Label = v1136,
				Title = v1136
			})
            local value15_80 = t1.value15
            local uDim2_135 = UDim2.new(0, 12, 0, 12)
            local uDim2_136 = UDim2.new(0, -5, 0.5)
            local vector2_49 = Vector2.new(1, 0.5)
            local v1141 = value15_80("ImageLabel", v1122, {
				Size = uDim2_135,
				Position = uDim2_136,
				AnchorPoint = vector2_49,
				Image = "rbxassetid://15637081879",
				BackgroundTransparency = 1
			})
            v1136.InputBegan:Connect(function(input)
                local v1635 = input.UserInputType == Enum.UserInputType.MouseButton1

                if not v1635 then
                    v1635 = input.UserInputType == Enum.UserInputType.Touch
                end

                if v1635 then
                    input:StopPropagation()
                end
            end)
            local t56 = {}
            local function v1143()
                local Text = v1136.Text

                if Text:gsub(" ", ""):len() > 0 then
                    if t56.OnChanging then
                        Text = t56.OnChanging(Text) or Text
                    end

                    t1.value16:FireCallback(Callback, Text)
                    v1136.Text = Text
                end
            end
            if v1100 then
                v1136.Text = v1100
            end
            v1136.FocusLost:Connect(v1143)
            v1143()
            v1136.FocusLost:Connect(function()
                t1.value29({
					v1141,
					"ImageColor3",
					Color3.fromRGB(255, 255, 255),
					0.2
				})
            end)
            v1136.Focused:Connect(function()
                t1.value29({
					v1141,
					"ImageColor3",
					t1.value32["Color Theme"],
					0.2
				})
            end)
            t56.OnChanging = false
            function t56.Visible(_, ...)
                t1.value16:ToggleVisible(v1115, ...)
            end
            function t56.Destroy(_)
                v1115:Destroy()
            end
            function t56.Set(_, p269)
                if type(p269) == "string" then
                    v1136.Text = p269
                    v1143()
                end
            end
            function t56.Get(_)
                return v1136.Text
            end

            return t56
        end
        function t33.AddDiscordInvite(_, p272)
            local v1146 = p272[1]

            if not v1146 then
                v1146 = p272.Name

                if not v1146 then
                    v1146 = p272.Title or "Discord"
                end
            end

            local Desc = p272.Desc

            if not Desc then
                Desc = p272.Description or ""
            end

            local v1148 = p272[2]

            if not v1148 then
                v1148 = p272.Logo or ""
            end

            local v1149 = p272[3]

            if not v1149 then
                v1149 = p272.Invite or ""
            end

            local v1150 = v1149
            local v1151 = t1.value15("Frame", v607, {
				Size = UDim2.new(1, 0, 0, 80),
				Name = "Option",
				BackgroundTransparency = 1
			})
            local value15_81 = t1.value15
            local uDim2_137 = UDim2.new(1, 0, 0, 15)
            local uDim2_138 = UDim2.new(0, 5)
            local color3_46 = Color3.fromRGB(40, 150, 255)
            local GothamBold = Enum.Font.GothamBold

            value15_81("TextLabel", v1151, {
				Size = uDim2_137,
				Position = uDim2_138,
				TextColor3 = color3_46,
				Font = GothamBold,
				TextXAlignment = "Left",
				BackgroundTransparency = 1,
				TextSize = 10,
				Text = v1150
			})

            local value13_36 = t1.value13
            local value15_82 = t1.value15
            local uDim2_139 = UDim2.new(1, 0, 0, 65)
            local vector2_50 = Vector2.new(0, 1)
            local uDim2_140 = UDim2.new(0, 0, 1)
            local v1162 = t1.value32["Color Hub 2"]
            local v1163 = value13_36(value15_82("Frame", v1151, {
				Size = uDim2_139,
				AnchorPoint = vector2_50,
				Position = uDim2_140,
				BackgroundColor3 = v1162
			}), "Frame")

            t1.value33("Corner", v1163)

            local value15_83 = t1.value15
            local uDim2_141 = UDim2.new(0, 30, 0, 30)
            local uDim2_142 = UDim2.new(0, 7, 0, 7)
            local v1167 = value15_83("ImageLabel", v1163, {
				Size = uDim2_141,
				Position = uDim2_142,
				Image = v1148,
				BackgroundTransparency = 1
			})

            t1.value33("Corner", v1167, UDim.new(0, 4))
            t1.value33("Stroke", v1167)

            local value13_37 = t1.value13
            local value15_84 = t1.value15
            local uDim2_143 = UDim2.new(1, -52, 0, 15)
            local uDim2_144 = UDim2.new(0, 44, 0, 7)
            local GothamBold4 = Enum.Font.GothamBold
            local v1173 = t1.value32["Color Text"]

            value13_37(value15_84("TextLabel", v1163, {
				Size = uDim2_143,
				Position = uDim2_144,
				Font = GothamBold4,
				TextColor3 = v1173,
				TextXAlignment = "Left",
				BackgroundTransparency = 1,
				TextSize = 10,
				Text = v1146
			}), "Text")

            local value13_38 = t1.value13
            local value15_85 = t1.value15
            local uDim2_145 = UDim2.new(1, -52, 0, 0)
            local uDim2_146 = UDim2.new(0, 44, 0, 22)
            local Gotham2 = Enum.Font.Gotham
            local v1179 = t1.value32["Color Dark Text"]

            value13_38(value15_85("TextLabel", v1163, {
				Size = uDim2_145,
				Position = uDim2_146,
				TextWrapped = "Y",
				AutomaticSize = "Y",
				Font = Gotham2,
				TextColor3 = v1179,
				TextXAlignment = "Left",
				BackgroundTransparency = 1,
				TextSize = 8,
				Text = Desc
			}), "DarkText")

            local value15_86 = t1.value15
            local uDim2_147 = UDim2.new(1, -14, 0, 16)
            local vector2_51 = Vector2.new(0.5, 1)
            local uDim2_148 = UDim2.new(0.5, 0, 1, -7)
            local GothamBold5 = Enum.Font.GothamBold
            local color3_47 = Color3.fromRGB(220, 220, 220)
            local color3_48 = Color3.fromRGB(255, 0, 0)
            local v1187 = value15_86("TextButton", v1163, {
				Size = uDim2_147,
				AnchorPoint = vector2_51,
				Position = uDim2_148,
				Text = "Join",
				Font = GothamBold5,
				TextSize = 12,
				TextColor3 = color3_47,
				BackgroundColor3 = color3_48
			})

            t1.value33("Corner", v1187, UDim.new(0, 5))
            v1187.Activated:Connect(function()
                setclipboard(v1150)

                local value12 = t1.value12
                local v1643 = v1187
                local color3_49 = Color3.fromRGB(100, 100, 100)
                local color3_50 = Color3.fromRGB(150, 150, 150)

                value12(v1643, {
					Text = "Copied to Clipboard",
					BackgroundColor3 = color3_49,
					TextColor3 = color3_50
				})
                task.wait(5)

                local value12_2 = t1.value12
                local v1647 = v1187
                local color3_51 = Color3.fromRGB(255, 0, 0)
                local color3_52 = Color3.fromRGB(220, 220, 220)

                value12_2(v1647, {
					Text = "Join",
					BackgroundColor3 = color3_51,
					TextColor3 = color3_52
				})
            end)

            return {
				Destroy = function(_)
                v1151:Destroy()
            end,
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v1151, ...)
            end
			}
        end
        function t33.AddSaveButtons(_, p276)
            if not p276 then
                p276 = "tab_save"
            end

            local v1190 = p276 .. ".json"

            if isfile and isfile(v1190) then
                local ok, result = pcall(function()
                    local value3 = t1.value3
                    local t57 = { readfile(v1190) }

                    return value3:JSONDecode(v2(t57))
                end)
                local v1193 = result

                if ok then
                    ok = type(v1193) == "table"
                end

                if ok then
                    task.defer(function()
                        for k, v in pairs(v1193) do
                            local v1656 = k

                            if t1.value11[v1656] ~= nil then
                                for _, v3 in pairs(t1.value7.Options) do
                                    local v1659 = v1656 == v3.Flag

                                    if v1659 then
                                        v1659 = v3.func

                                        if v1659 then
                                            v1659 = v3.func.Set
                                        end
                                    end

                                    if v1659 then
                                        v3.func:Set(v)
                                    end
                                end
                            end
                        end
                    end)
                end
            end

            t33:AddSection("ðŸ’¾ ConfiguraÃ§Ãµes")
            t33:AddButton({
				Name = "Salvar",
				Desc = "Salva o estado atual desta aba",
				Callback = function()
                local t58 = {}

                for k, v in pairs(t1.value11) do
                    t58[k] = v
                end

                if writefile then
                    writefile(v1190, t1.value3:JSONEncode(t58))
                end
            end
			})
            t33:AddButton({
				Name = "Resetar",
				Desc = "Desliga e zera tudo desta aba e salva",
				Callback = function()
                for _, v in pairs(t1.value7.Options) do
                    local func = v.func

                    if func then
                        func = v.func.Set
                    end

                    if func then
                        if v.type == "Toggle" then
                            v.func:Set(false)
                        elseif v.type == "Slider" then
                            v.func:Set(v.Default or (v.Min or 0))
                        end
                    end
                end

                local t59 = {}

                for k, _ in pairs(t1.value11) do
                    t59[k] = t1.value11[k]
                end

                if writefile then
                    writefile(v1190, t1.value3:JSONEncode(t59))
                end
            end
			})
        end
        function t33.AddConfigDesigner(_, p278)
            local v1196 = p278[1]

            if not v1196 then
                v1196 = p278.Name

                if not v1196 then
                    v1196 = p278.Title or "Designer"
                end
            end

            local Desc = p278.Desc

            if not Desc then
                Desc = p278.Description or "Salvar e carregar designs"
            end

            local v1198 = p278.SaveButtonName or "Salvar Config"

            if not p278.LoadButtonName then
            end

            local v1199 = p278.DeleteButtonName or "Apagar Config"
            local v1200 = p278.LuaImages or {}
            local v1201 = p278.SkullImages or {}
            local v1202 = p278.BgImages or {}

            local function v1203()
                pcall(function()
                    local _makefolder = makefolder

                    if _makefolder then
                        _makefolder = isfolder and not isfolder("炎.config.Spectra")
                    end

                    if _makefolder then
                        makefolder("炎.config.Spectra")
                    end
                end)
            end
            local function v1204()
                local t60 = { "Nenhum" }
                if not listfiles or not isfolder then
                    return t60
                end
                local ok, result = pcall(listfiles, "炎.config.Spectra")
                local v1672 = not ok
                if not v1672 then
                    v1672 = type(result) ~= "table"
                end
                if v1672 then
                    return t60
                end
                local t61 = {}
                for v1676, v1677 in ipairs(result) do

                    local v1678 = (v1677:match("([^/\\]+)$") or v1677):match("^Config(%d+)%.txt$")

                    if v1678 then
                        table.insert(t61, (tonumber(v1678)))
                    end
                end
                table.sort(t61)
                for _, v in ipairs(t61) do
                    local v1681 = "炎.config.Spectra" .. "/Config" .. v .. ".txt"
                    local v1682 = "Config " .. v
                    local _isfile = isfile

                    if _isfile then
                        _isfile = isfile(v1681) and readfile
                    end

                    if _isfile then
                        local ok4, result4 = pcall(function()
                            local value3 = t1.value3
                            local t62 = { readfile(v1681) }

                            return value3:JSONDecode(v2(t62))
                        end)

                        if ok4 then
                            ok4 = type(result4) == "table"

                            if ok4 then
                                ok4 = type(result4.Name) == "string"

                                if ok4 then
                                    ok4 = #result4.Name:gsub(" ", "") > 0
                                end
                            end
                        end

                        if ok4 then
                            v1682 = result4.Name .. " [" .. v .. "]"
                        end
                    end

                    table.insert(t60, v1682)
                end

                return t60
            end
            local function v1205()
                if not listfiles or not isfolder then
                    return 1
                end

                local ok, result = pcall(listfiles, "炎.config.Spectra")
                local v1688 = not ok

                if not v1688 then
                    v1688 = type(result) ~= "table"
                end

                if v1688 then
                    return 1
                end

                local t63 = {}

                for _, v in ipairs(result) do
                    local v1692 = (v:match("([^/\\]+)$") or v):match("^Config(%d+)%.txt$")

                    if v1692 then
                        t63[tonumber(v1692)] = true
                    end
                end

                local n10 = 1

                while t63[n10] do
                    n10 += 1
                end

                return n10
            end
            local function v1206(p279, p280)
                local _tostring = tostring

                if not p280 then
                    p280 = ""
                end

                local v1697 = _tostring(p280):gsub("rbxassetid://", "")

                for k, v in pairs(p279) do
                    local _tostring2 = tostring
                    local v1701 = v

                    if not v then
                        v1701 = ""
                    end

                    if v1697 == _tostring2(v1701):gsub("rbxassetid://", "") then
                        return k
                    end
                end

                return nil
            end
            local function v1207(p281)
                local s2 = "Vermelho"

                for k, v in pairs(t12.value12) do
                    if v == t12.value6 then
                        s2 = k

                        break
                    end
                end

                local v1706 = v1206(v1200, t12.value25.Image) or "Nenhum"
                local v1707 = v1206(v1201, t12.value30.Image) or "nenhum"
                local v1708 = v1206(v1202, t12.value1.Image)

                if not v1708 or v1708 == "" then
                    v1708 = "Nenhum imagem"
                end

                local v1709 = type(p281) == "string" and (#p281:gsub(" ", "") > 0 and p281) or "Config"
                local v1710 = t12.value1.Image ~= ""

                if v1710 then
                    v1710 = t12.value1.Image
                end

                local v1711 = v1710 or ""
                local value3 = t12.value3
                local value21 = t12.value21
                local value25Image = t12.value25.Image
                local value20 = t12.value20
                local value23 = t12.value23
                local value24 = t12.value24
                local value29 = t12.value29
                local value30Image = t12.value30.Image
                local value33 = t12.value33
                local value32 = t12.value32
                local value4 = t12.value4
                local value7 = t12.value7
                local value10_2 = t12.value10
                local value23_2 = t1.value23
                local value24_2 = t1.value24
                local Toggle = t1.value34.Toggle
                local Button = t1.value34.Button
                local Paragraph = t1.value34.Paragraph
                local Dropdown = t1.value34.Dropdown
                local Slider = t1.value34.Slider
                local TextBox = t1.value34.TextBox
                local Section = t1.value34.Section

                return {
					Name = v1709,
					BgNome = v1708,
					BgAssetId = v1711,
					Transparency = value3,
					LuaEnabled = value21,
					LuaNome = v1706,
					LuaAssetId = value25Image,
					LuaSpeed = value20,
					LuaSize = value23,
					LuaBrightness = value24,
					SkullEnabled = value29,
					SkullNome = v1707,
					SkullAssetId = value30Image,
					ParticlesEnabled = value33,
					ParticleColor = value32,
					GlowEnabled = value4,
					GlowColor = s2,
					GlowIntense = value7,
					TabGlowEnabled = value10_2,
					SoundEnabled = value23_2,
					SoundId = value24_2,
					TextSizeToggle = Toggle,
					TextSizeButton = Button,
					TextSizeParagraph = Paragraph,
					TextSizeDropdown = Dropdown,
					TextSizeSlider = Slider,
					TextSizeTextBox = TextBox,
					TextSizeSection = Section
				}
            end
            local function v1208()
                pcall(function()
                    t12.value49:SetBackground("")
                end)
                pcall(function()
                    t12.value49:SetWindowTransparency(0.03)
                end)
                pcall(function()
                    t12.value49:SetLua(false)
                end)
                pcall(function()
                    t12.value49:SetLuaImage("")
                end)
                pcall(function()
                    t12.value49:SetSkull(false)
                end)
                pcall(function()
                    t12.value49:SetSkullImage("")
                end)
                pcall(function()
                    t12.value49:SetParticles(false)
                end)
                pcall(function()
                    t12.value49:SetGlow(false)
                end)
                pcall(function()
                    t12.value49:SetTabGlow(false)
                end)
                pcall(function()
                    t12.value49:SetSound(false)
                end)
            end
            local function v1209(p282)
                if type(p282) ~= "table" then
                    return
                end

                pcall(function()
                    local s3 = ""
                    local v1900 = type(p282.BgNome) == "string"

                    if v1900 then
                        v1900 = v1202[p282.BgNome] ~= nil
                    end

                    if v1900 then
                        s3 = v1202[p282.BgNome]
                    elseif type(p282.BgAssetId) == "string" then
                        s3 = p282.BgAssetId
                    end

                    t12.value49:SetBackground(s3)
                end)
                pcall(function()
                    if type(p282.Transparency) == "number" then
                        t12.value49:SetWindowTransparency(p282.Transparency)
                    end
                end)
                pcall(function()
                    local s4 = ""
                    local v1902 = type(p282.LuaNome) == "string"

                    if v1902 then
                        v1902 = v1200[p282.LuaNome] ~= nil
                    end

                    if v1902 then
                        s4 = v1200[p282.LuaNome]
                    else
                        local v1903 = type(p282.LuaAssetId) == "string"

                        if v1903 then
                            v1903 = #p282.LuaAssetId > 0
                        end

                        if v1903 then
                            s4 = p282.LuaAssetId
                        end
                    end

                    t12.value49:SetLuaImage(s4)
                end)
                pcall(function()
                    if type(p282.LuaSpeed) == "number" then
                        t12.value49:SetLuaSpeed(p282.LuaSpeed)
                    end
                end)
                pcall(function()
                    if type(p282.LuaSize) == "number" then
                        t12.value49:SetLuaSize(p282.LuaSize)
                    end
                end)
                pcall(function()
                    if type(p282.LuaBrightness) == "number" then
                        t12.value49:SetLuaBrightness(p282.LuaBrightness)
                    end
                end)
                pcall(function()
                    if type(p282.LuaEnabled) == "boolean" then
                        t12.value49:SetLua(p282.LuaEnabled)
                    end
                end)
                pcall(function()
                    local s5 = ""
                    local v1905 = type(p282.SkullNome) == "string"

                    if v1905 then
                        v1905 = v1201[p282.SkullNome] ~= nil
                    end

                    if v1905 then
                        s5 = v1201[p282.SkullNome]
                    else
                        local v1906 = type(p282.SkullAssetId) == "string"

                        if v1906 then
                            v1906 = #p282.SkullAssetId > 0
                        end

                        if v1906 then
                            s5 = p282.SkullAssetId
                        end
                    end

                    t12.value49:SetSkullImage(s5)
                end)
                pcall(function()
                    if type(p282.SkullEnabled) == "boolean" then
                        t12.value49:SetSkull(p282.SkullEnabled)
                    end
                end)
                pcall(function()
                    if type(p282.ParticleColor) == "string" then
                        t12.value49:SetParticleColor(p282.ParticleColor)
                    end
                end)
                pcall(function()
                    if type(p282.ParticlesEnabled) == "boolean" then
                        t12.value49:SetParticles(p282.ParticlesEnabled)
                    end
                end)
                pcall(function()
                    if type(p282.GlowColor) == "string" then
                        t12.value49:SetGlowColor(p282.GlowColor)
                    end
                end)
                pcall(function()
                    if type(p282.GlowIntense) == "boolean" then
                        t12.value49:SetGlowIntensity(p282.GlowIntense)
                    end
                end)
                pcall(function()
                    if type(p282.GlowEnabled) == "boolean" then
                        t12.value49:SetGlow(p282.GlowEnabled)
                    end
                end)
                pcall(function()
                    if type(p282.TabGlowEnabled) == "boolean" then
                        t12.value49:SetTabGlow(p282.TabGlowEnabled)
                    end
                end)
                pcall(function()
                    if type(p282.SoundId) == "string" then
                        t12.value49:SetSoundId(p282.SoundId)
                    end
                end)
                pcall(function()
                    if type(p282.SoundEnabled) == "boolean" then
                        t12.value49:SetSound(p282.SoundEnabled)
                    end
                end)
                pcall(function()
                    if type(p282.TextSizeToggle) == "number" then
                        t12.value49:SetElementTextSize("Toggle", p282.TextSizeToggle)
                    end
                end)
                pcall(function()
                    if type(p282.TextSizeButton) == "number" then
                        t12.value49:SetElementTextSize("Button", p282.TextSizeButton)
                    end
                end)
                pcall(function()
                    if type(p282.TextSizeParagraph) == "number" then
                        t12.value49:SetElementTextSize("Paragraph", p282.TextSizeParagraph)
                    end
                end)
                pcall(function()
                    if type(p282.TextSizeDropdown) == "number" then
                        t12.value49:SetElementTextSize("Dropdown", p282.TextSizeDropdown)
                    end
                end)
                pcall(function()
                    if type(p282.TextSizeSlider) == "number" then
                        t12.value49:SetElementTextSize("Slider", p282.TextSizeSlider)
                    end
                end)
                pcall(function()
                    if type(p282.TextSizeTextBox) == "number" then
                        t12.value49:SetElementTextSize("TextBox", p282.TextSizeTextBox)
                    end
                end)
                pcall(function()
                    if type(p282.TextSizeSection) == "number" then
                        t12.value49:SetElementTextSize("Section", p282.TextSizeSection)
                    end
                end)
                pcall(function()
                    if type(p282.TextSizeColorPicker) == "number" then
                        t12.value49:SetElementTextSize("ColorPicker", p282.TextSizeColorPicker)
                    end
                end)
                pcall(function()
                    t1.value18:FireConnection("DesignApplied", p282)
                end)
            end

            t33:AddSection(v1196)

            local v1210 = Desc

            if Desc then
                v1210 = #Desc:gsub(" ", "") > 0
            end

            if v1210 then
                t33:AddParagraph({
					v1196,
					Desc
				})
            end

            local s6 = "Nenhum"

            local function v1212(p283)
                if not p283 then
                    return
                end

                if p283 == "Nenhum" then
                    v1208()

                    return
                end

                if not readfile or not isfile then
                    return
                end

                local v1736 = p283:match("%[(%d+)%]$")

                if not v1736 then
                    v1736 = p283:match("^Config (%d+)$")
                end

                if not v1736 then
                    return
                end

                local v1737 = "炎.config.Spectra" .. "/Config" .. v1736 .. ".txt"
                local ok, result = pcall(isfile, v1737)
                local v1740 = not ok

                if not v1740 then
                    v1740 = not result
                end

                if v1740 then
                    return
                end

                local ok5, result5 = pcall(readfile, v1737)
                local v1743 = result5
                local v1744 = not ok5

                if not v1744 then
                    v1744 = type(v1743) ~= "string"
                end

                if v1744 then
                    return
                end

                local ok6, result6 = pcall(function()
                    return t1.value3:JSONDecode(v1743)
                end)

                if ok6 then
                    ok6 = type(result6) == "table"
                end

                if ok6 then
                    v1209(result6)
                end
            end

            local v1213 = v1204()
            local v1214 = t33:AddDropdown({
				Name = "Configs Salvas",
				Desc = "Clique no nome pra aplicar na hora",
				Options = v1213,
				Default = "Nenhum",
				Callback = function(p284)
                if not p284 then
                    p284 = "Nenhum"
                end

                s6 = p284
                v1212(s6)
            end
			})
            local s7 = ""

            t33:AddTextBox({
				Name = "Nome da Config",
				Desc = "Ex: Tema Vermelho, Lua Grande...",
				PlaceholderText = "Nome da config",
				ClearText = false,
				Callback = function(p285)
                if not p285 then
                    p285 = ""
                end

                s7 = p285
            end
			})
            t33:AddButton({
				Name = v1198,
				Desc = "Salva o design visual atual",
				Callback = function()
                if not writefile then
                    return
                end
                v1203()
                local v1750 = "炎.config.Spectra" .. "/Config" .. v1205() .. ".txt"
                local v1752 = v1207(s7)
                local u1753 = v1752
                local ok, result = pcall(function()
                    return t1.value3:JSONEncode(u1753)
                end)
                if ok and result then
                    pcall(writefile, v1750, result)

                    local v1756 = v1204()

                    s6 = "Nenhum"
                    v1214:Set(v1756, true)
                    v1214:Select("Nenhum")
                    v1208()
                end
            end
			})
            t33:AddButton({
				Name = v1199,
				Desc = "Apaga a config selecionada",
				Callback = function()
                local v1757 = not s6

                if not v1757 then
                    v1757 = s6 == "Nenhum"
                end

                if v1757 then
                    return
                end

                local v1758 = s6:match("%[(%d+)%]$")

                if not v1758 then
                    v1758 = s6:match("^Config (%d+)$")
                end

                if not v1758 then
                    return
                end

                local v1759 = "炎.config.Spectra" .. "/Config" .. v1758 .. ".txt"
                local _delfile = delfile

                if _delfile then
                    _delfile = isfile and isfile(v1759)
                end

                if _delfile then
                    delfile(v1759)
                end

                local v1761 = v1204()

                s6 = "Nenhum"
                v1214:Set(v1761, true)
                v1214:Select("Nenhum")
                v1208()
            end
			})

            return {
				Refresh = function(_)
                local v1763 = v1204()

                s6 = "Nenhum"
                v1214:Set(v1763, true)
                v1214:Select("Nenhum")
                v1208()
            end,
				Apply = function(_, p288)
                v1209(p288)
            end,
				Capture = function(_, p290)
                return v1207(p290)
            end
			}
        end
        function t33.AddMultiDropdown(_, p292)
            local v1218 = p292[1]
            if not v1218 then
                v1218 = p292.Name

                if not v1218 then
                    v1218 = p292.Title or "Multi Dropdown"
                end
            end
            local Desc = p292.Desc
            if not Desc then
                Desc = p292.Description or ""
            end
            local v1220 = p292[2]
            if not v1220 then
                v1220 = p292.Options or {}
            end
            local v1221 = p292[3]
            if not v1221 then
                v1221 = p292.Default or {}
            end
            local v1222 = p292[5] or (p292.Flag or false)
            local Callback = t1.value16:GetCallback(p292, 4)
            local v1224, _ = t1.value36(v607, v1218, Desc, UDim2.new(1, -180))
            local v1226 = v1224
            local value13_39 = t1.value13
            local value15_87 = t1.value15
            local uDim2_149 = UDim2.new(0, 150, 0, 18)
            local uDim2_150 = UDim2.new(1, -10, 0.5)
            local vector2_52 = Vector2.new(1, 0.5)
            local v1232 = t1.value32["Color Stroke"]
            local v1233 = value13_39(value15_87("Frame", v1226, {
				Size = uDim2_149,
				Position = uDim2_150,
				AnchorPoint = vector2_52,
				BackgroundColor3 = v1232
			}), "Stroke")
            t1.value33("Corner", v1233, UDim.new(0, 4))
            local value13_40 = t1.value13
            local value15_88 = t1.value15
            local uDim2_151 = UDim2.new(0.85, 0, 0.85, 0)
            local vector2_53 = Vector2.new(0.5, 0.5)
            local uDim2_152 = UDim2.new(0.5, 0, 0.5, 0)
            local GothamBold = Enum.Font.GothamBold
            local v1240 = t1.value32["Color Text"]
            local v1241 = value13_40(value15_88("TextLabel", v1233, {
				Size = uDim2_151,
				AnchorPoint = vector2_53,
				Position = uDim2_152,
				BackgroundTransparency = 1,
				Font = GothamBold,
				TextScaled = true,
				TextColor3 = v1240,
				Text = "..."
			}), "Text")
            table.insert(t1.value35.Dropdown, {
				Title = v1241,
				Label = v1241
			})
            local value15_89 = t1.value15
            local uDim2_153 = UDim2.new(0, 15, 0, 15)
            local uDim2_154 = UDim2.new(0, -5, 0.5)
            local vector2_54 = Vector2.new(1, 0.5)
            local v1246 = value15_89("ImageLabel", v1233, {
				Size = uDim2_153,
				Position = uDim2_154,
				AnchorPoint = vector2_54,
				Image = "rbxassetid://10709791523",
				BackgroundTransparency = 1
			})
            local value15_90 = t1.value15
            local value13_41 = t12.value13
            local uDim2_155 = UDim2.new(1, 0, 1, 0)
            local v1250 = value15_90("TextButton", value13_41, {
				Name = "AntiClick",
				Size = uDim2_155,
				BackgroundTransparency = 1,
				Visible = false,
				Text = ""
			})
            local value15_91 = t1.value15
            local uDim2_156 = UDim2.fromOffset(152, 0)
            local color3_53 = Color3.fromRGB(255, 255, 255)
            local vector2_55 = Vector2.new(0, 1)
            local v1255 = value15_91("Frame", v1250, {
				Size = uDim2_156,
				BackgroundTransparency = 0.1,
				BackgroundColor3 = color3_53,
				AnchorPoint = vector2_55,
				Name = "DropdownFrame",
				ClipsDescendants = true,
				Active = true
			})
            t1.value33("Corner", v1255)
            t1.value33("Stroke", v1255)
            t1.value33("Gradient", v1255, {
				Rotation = 60
			})
            local value13_42 = t1.value13
            local value15_92 = t1.value15
            local v1258 = t1.value32["Color Theme"]
            local uDim2_157 = UDim2.new(1, 0, 1, -5)
            local uDim2_158 = UDim2.new(0, 0, 0, 5)
            local uDim2_159 = UDim2.new()
            local t64 = {
				ScrollBarImageColor3 = v1258,
				Size = uDim2_157,
				Position = uDim2_158,
				ScrollBarThickness = 1.5,
				BackgroundTransparency = 1,
				BorderSizePixel = 0,
				CanvasSize = uDim2_159,
				ScrollingDirection = "Y",
				AutomaticCanvasSize = "Y",
				Active = true
			}
            local value15_93 = t1.value15
            local uDim23 = UDim.new(0, 8)
            local uDim24 = UDim.new(0, 8)
            local uDim25 = UDim.new(0, 5)
            local uDim26 = UDim.new(0, 5)
            local v1268 = value13_42(value15_92("ScrollingFrame", v1255, t64, {
				value15_93("UIPadding", {
					PaddingLeft = uDim23,
					PaddingRight = uDim24,
					PaddingTop = uDim25,
					PaddingBottom = uDim26
				}),
				t1.value15("UIListLayout", {
					Padding = UDim.new(0, 4)
				})
			}), "ScrollBar")
            local n11 = 5
            local u1270
            local t65 = {}
            local function v1272()
                t1.value29({
					v1246,
					"Rotation",
					0,
					0.25
				})
                t1.value29({
					v1255,
					"Size",
					UDim2.new(0, 152, 0, 0),
					0.25
				})
                t1.value29({
					v1246,
					"ImageColor3",
					Color3.fromRGB(255, 255, 255),
					0.25
				})
                v1246.Image = "rbxassetid://10709791523"
                v1250.Visible = false
                u1270 = false
            end
            local function v1273()
                local n12 = 0

                for _, child in pairs(v1268:GetChildren()) do
                    if child:IsA("TextButton") and child.Visible then
                        n12 += 1
                    end
                end

                n11 = math.clamp(n12, 0, 10) * 30 + 10

                if v1250.Visible then
                    t1.value29({
						v1255,
						"Size",
						UDim2.fromOffset(152, n11),
						0.2
					})
                end
            end
            local function v1274()
                local AbsolutePosition = v1233.AbsolutePosition
                local AbsoluteSize = t1.value22.AbsoluteSize
                local v1773 = math.clamp(AbsolutePosition.X / t1.value9, 0, AbsoluteSize.X / t1.value9 - v1255.Size.X.Offset)
                local v1774 = math.clamp(AbsolutePosition.Y / t1.value9, 0, AbsoluteSize.Y / t1.value9)
                local uDim2_160 = UDim2.fromOffset(v1773, v1774)
                local v1776 = if not (AbsolutePosition.Y > AbsoluteSize.Y / 1.4) then not (n11 > 80) and 0 or 0.5 else 1

                v1255.AnchorPoint = Vector2.new(0, v1776)
                t1.value29({
					v1255,
					"Position",
					uDim2_160,
					0.1
				})
            end
            local u1275
            local u1276
            local u1277
            local u1278
            local v1279 = type(v1221) ~= "table" and { v1221 } or v1221
            local t66 = {}
            if type(v1222) == "string" and t1.value11[v1222] ~= nil then
                local v1281 = t1.value19(v1222)

                if type(v1281) == "table" then
                    for k, v in pairs(v1281) do
                        if v then
                            t66[tostring(k)] = true
                        end
                    end
                end
            else
                for _, v in pairs(v1279) do
                    t66[tostring(v)] = true
                end
            end
            local u1286
            local function v1287()
                t1.value20(v1222, t66)
                t1.value16:FireCallback(Callback, u1278())
            end
            local function v1288()
                local v1807 = u1278()
                local v1808 = v1241
                local v1809 = #v1807 > 0

                if v1809 then
                    v1809 = table.concat(v1807, ", ")
                end

                v1808.Text = v1809 or "..."
            end
            function u1286()
                for _, v in pairs(t65) do
                    local nodes = v.nodes
                    local Stats = v.Stats

                    t1.value29({
						nodes[2],
						"BackgroundTransparency",
						not Stats and 0.8 or 0,
						0.35
					})

                    local value29 = t1.value29
                    local v1821 = nodes[2]
                    local v1822 = Stats

                    if Stats then
                        v1822 = UDim2.fromOffset(4, 12)
                    end

                    if not v1822 then
                        v1822 = UDim2.fromOffset(4, 4)
                    end

                    value29({
						v1821,
						"Size",
						v1822,
						0.35
					})
                    t1.value29({
						nodes[3],
						"TextTransparency",
						not Stats and 0.4 or 0,
						0.35
					})
                end

                v1288()
            end
            function u1277(p293)
                p293.Stats = not p293.Stats
                t66[p293.Name] = p293.Stats or nil
                v1287()
                u1286()
            end
            function u1275(p294, p295)
                local str = tostring(type(p294) == "string" and p294 or p295)

                if t65[str] then
                    return
                end

                local v1783 = t66[str] or false
                local t67 = {
					index = p294,
					Value = p295,
					Name = str,
					Stats = v1783,
					LastCB = 0
				}
                local value33 = t1.value33
                local v1786 = v1268
                local uDim2_161 = UDim2.new(1, 0, 0, 26)
                local uDim2_162 = UDim2.new(0, 0, 0.5)
                local vector2_56 = Vector2.new(0, 0.5)
                local v1790 = value33("Button", v1786, {
					Name = "Option",
					Size = uDim2_161,
					Position = uDim2_162,
					AnchorPoint = vector2_56
				})

                t1.value33("Corner", v1790, UDim.new(0, 4))

                local value13_43 = t1.value13
                local value15_94 = t1.value15
                local uDim2_163 = UDim2.new(0, 1, 0.5)
                local v1794 = v1783

                if v1783 then
                    v1794 = UDim2.fromOffset(4, 12)
                end

                if not v1794 then
                    v1794 = UDim2.fromOffset(4, 4)
                end

                local v1795 = t1.value32["Color Theme"]
                local v1796 = not v1783 and 0.8 or 0
                local vector2_57 = Vector2.new(0, 0.5)
                local v1798 = value13_43(value15_94("Frame", v1790, {
					Position = uDim2_163,
					Size = v1794,
					BackgroundColor3 = v1795,
					BackgroundTransparency = v1796,
					AnchorPoint = vector2_57
				}), "Theme")

                t1.value33("Corner", v1798, UDim.new(0.5, 0))

                local value13_44 = t1.value13
                local value15_95 = t1.value15
                local uDim2_164 = UDim2.new(1, 0, 1)
                local uDim2_165 = UDim2.new(0, 10)
                local v1803 = t1.value32["Color Text"]
                local GothamBold6 = Enum.Font.GothamBold
                local v1805 = not v1783 and 0.4 or 0
                local v1806 = value13_44(value15_95("TextLabel", v1790, {
					Size = uDim2_164,
					Position = uDim2_165,
					Text = str,
					TextColor3 = v1803,
					Font = GothamBold6,
					TextXAlignment = "Left",
					BackgroundTransparency = 1,
					TextTransparency = v1805
				}), "Text")

                v1790.Activated:Connect(function()
                    local v1907 = t65[str]

                    u1277(v1907)
                end)
                t67.nodes = {
					v1790,
					v1798,
					v1806
				}
                t65[str] = t67
            end
            function u1276(p296, p297)
                local str = tostring(type(p296) == "string" and p296 or p297)

                if t65[str] then
                    t66[str] = nil
                    t65[str].nodes[1]:Destroy()
                    table.clear(t65[str])
                    t65[str] = nil
                end
            end
            local function v1289()
                return t65
            end
            function u1278()
                local t68 = {}

                for _, v in pairs(t65) do
                    if v.Stats then
                        table.insert(t68, v.Name)
                    end
                end

                table.sort(t68)

                return t68
            end
            local function v1290(p298, p299)
                if p299 then
                    for _, v in pairs(t65) do
                        u1276(v.index, v.Value)
                    end
                end

                for k, v in pairs(p298) do
                    u1275(k, v)
                end

                v1287()
                u1286()
            end
            for k, v in pairs(v1220) do
                u1275(k, v)
            end
            v1287()
            u1286()
            v1226.Activated:Connect(function()
                if u1270 then
                    return
                end

                if v1250.Visible then
                    v1246.Image = "rbxassetid://10709791523"
                    t1.value29({
						v1246,
						"ImageColor3",
						Color3.fromRGB(255, 255, 255),
						0.25
					})
                    t1.value29({
						v1255,
						"Size",
						UDim2.new(0, 152, 0, 0),
						0.25
					})
                    v1250.Visible = false

                    return
                end

                v1250.Visible = true
                v1246.Image = "rbxassetid://10709790948"
                t1.value29({
					v1246,
					"ImageColor3",
					t1.value32["Color Theme"],
					0.25
				})
                t1.value29({
					v1255,
					"Size",
					UDim2.fromOffset(152, n11),
					0.3
				})
            end)
            v1250.MouseButton1Down:Connect(v1272)
            v1250.MouseButton1Click:Connect(v1272)
            t12.value1:GetPropertyChangedSignal("Visible"):Connect(v1272)
            v1233:GetPropertyChangedSignal("AbsolutePosition"):Connect(v1274)
            v1226.Activated:Connect(v1273)
            v1268.ChildAdded:Connect(v1273)
            v1268.ChildRemoved:Connect(v1273)
            v1274()
            v1273()

            return {
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v1226, ...)
            end,
				Destroy = function(_)
                v1226:Destroy()
            end,
				Callback = function(_, ...)
                t1.value16:InsertCallback(Callback, ...)(u1278())
            end,
				Get = function(_)
                return u1278()
            end,
				Add = function(_, ...)
                for _, v in ipairs({ ... }) do
                    u1275(v, v)
                end
            end,
				Remove = function(_, p306)
                for k, v in pairs(v1289()) do
                    local v1838 = k

                    if type(p306) == "number" and v1838 == p306 or p306 == v.Name then
                        u1276(v1838, v.Value)
                    end
                end
            end,
				Select = function(_, p308)
                for _, v in pairs(t65) do
                    if v.Name == tostring(p308) and not v.Stats then
                        u1277(v)
                    end
                end
            end,
				Deselect = function(_, p310)
                for _, v in pairs(t65) do
                    if v.Name == tostring(p310) and v.Stats then
                        u1277(v)
                    end
                end
            end,
				Set = function(_, p312, p313)
                if type(p312) == "table" then
                    v1290(p312, not p313)

                    return
                end

                if type(p312) ~= "function" then
                end
            end
			}
        end
        function t33.AddSeparator(_, p315)
            if not p315 then
                p315 = {}
            end

            local v1295 = p315.Thickness or (p315[1] or 1)
            local v1296 = p315.Padding or 6
            local v1297 = t1.value15("Frame", v607, {
				Size = UDim2.new(1, 0, 0, v1296 * 2 + v1295),
				BackgroundTransparency = 1,
				Name = "Option"
			})
            local value13_45 = t1.value13
            local value15_96 = t1.value15
            local uDim2_166 = UDim2.new(1, 0, 0, v1295)
            local uDim2_167 = UDim2.new(0, 0, 0.5)
            local vector2_58 = Vector2.new(0, 0.5)
            local v1303 = t1.value32["Color Stroke"]

            value13_45(value15_96("Frame", v1297, {
				Size = uDim2_166,
				Position = uDim2_167,
				AnchorPoint = vector2_58,
				BackgroundColor3 = v1303,
				BackgroundTransparency = 0.15,
				BorderSizePixel = 0
			}), "Stroke")

            return {
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v1297, ...)
            end,
				Destroy = function(_)
                v1297:Destroy()
            end
			}
        end
        function t33.AddSpace(_, p319)
            if not p319 then
                p319 = {}
            end
            local Width = p319.Width
            if not Width then
                Width = p319.Height or (p319[1] or 10)
            end
            local p319Color = p319.Color
            local Gradient = p319.Gradient
            local v1309 = t1.value15("Frame", v607, {
				Size = UDim2.new(1, 0, 0, Width),
				BackgroundTransparency = 1,
				Name = "Option"
			})
            local u1310
            local function v1311()
                if u1310 then
                    u1310:Destroy()
                    u1310 = nil
                end

                if not p319Color and not Gradient then
                    return
                end

                local value15_97 = t1.value15
                local v1853 = v1309
                local uDim2_168 = UDim2.new(1, 0, 1, 0)
                local uDim2_169 = UDim2.new(0.5, 0, 0.5, 0)
                local vector2_59 = Vector2.new(0.5, 0.5)
                local v1857 = p319Color

                if not v1857 then
                    v1857 = Color3.fromRGB(255, 255, 255)
                end

                u1310 = value15_97("Frame", v1853, {
					Size = uDim2_168,
					Position = uDim2_169,
					AnchorPoint = vector2_59,
					BackgroundColor3 = v1857,
					BorderSizePixel = 0
				})
                t1.value33("Corner", u1310, UDim.new(1, 0))

                if type(Gradient) == "table" and #Gradient > 0 then
                    if #Gradient == 1 then
                        u1310.BackgroundColor3 = Gradient[1]

                        return
                    end

                    local t69 = {}
                    local v1859 = #Gradient

                    for i, v in ipairs(Gradient) do
                        local v1862 = (i - 1) / (v1859 - 1)

                        table.insert(t69, ColorSequenceKeypoint.new(v1862, v))
                    end

                    t1.value15("UIGradient", u1310, {
						Color = ColorSequence.new(t69)
					})
                end
            end
            v1311()

            return {
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v1309, ...)
            end,
				Destroy = function(_)
                v1309:Destroy()
            end,
				Set = function(_, p323)
                if type(p323) == "number" then
                    t1.value29({
							v1309,
							"Size",
							UDim2.new(1, 0, 0, p323),
							0.2
						})
                end
            end,
				SetColor = function(_, p325)
                p319Color = p325
                Gradient = nil
                v1311()
            end,
				SetGradient = function(_, p327)
                Gradient = p327
                v1311()
            end
			}
        end
        function t33.AddBanner(_, p329)
            if not p329 then
                p329 = {}
            end

            local p329Image = p329.Image

            if not p329Image then
                p329Image = p329[1] or ""
            end

            local p329Title = p329.Title

            if not p329Title then
                p329Title = p329[2] or "Banner"
            end

            local Description = p329.Description

            if not Description then
                Description = p329.Desc

                if not Description then
                    Description = p329[3] or ""
                end
            end

            local v1317 = p329.Height or 120
            local v1318 = p329.ScaleType or "Fit"
            local Callback = t1.value16:GetCallback(p329, 4)
            local Fit3 = Enum.ScaleType.Fit
            local Crop = Enum.ScaleType.Crop
            local Stretch = Enum.ScaleType.Stretch
            local t70 = {
				Fit = Fit3,
				Crop = Crop,
				Stretch = Stretch
			}
            local v1324 = t1.value15("TextButton", v607, {
				Size = UDim2.new(1, 0, 0, v1317),
				Name = "Option",
				BackgroundTransparency = 1,
				AutoButtonColor = false,
				Text = ""
			})

            t1.value33("Shadow", v1324, {
				Spread = 18,
				Transparency = 0.65
			})

            local value13_46 = t1.value13
            local value15_98 = t1.value15
            local uDim2_170 = UDim2.new(1, 0, 1, 0)
            local v1328 = t1.value32["Color Hub 2"]
            local v1329 = value13_46(value15_98("Frame", v1324, {
				Size = uDim2_170,
				BackgroundColor3 = v1328,
				ClipsDescendants = true
			}), "Frame")

            t1.value33("Corner", v1329)
            t1.value33("Stroke", v1329)

            local value13_47 = t1.value13
            local value15_99 = t1.value15
            local uDim2_171 = UDim2.new(1, 0, 1, 0)
            local v1333 = t1.value32["Color Hub 2"]

            value13_47(value15_99("Frame", v1329, {
				Size = uDim2_171,
				BackgroundColor3 = v1333,
				BorderSizePixel = 0
			}), "Frame")

            local value15_100 = t1.value15
            local uDim2_172 = UDim2.new(1, 0, 1, 0)
            local v1336 = t70[v1318]

            if not v1336 then
                v1336 = Enum.ScaleType.Fit
            end

            local Icon3 = t1.value7:GetIcon(p329Image)
            local v1338 = value15_100("ImageLabel", v1329, {
				Size = uDim2_172,
				BackgroundTransparency = 1,
				ScaleType = v1336,
				Image = Icon3
			})
            local value15_101 = t1.value15
            local uDim2_173 = UDim2.new(1, 0, 1, 0)
            local color3_54 = Color3.fromRGB(0, 0, 0)
            local v1342 = value15_101("Frame", v1329, {
				Size = uDim2_173,
				BackgroundColor3 = color3_54,
				BackgroundTransparency = 0.35,
				BorderSizePixel = 0,
				ZIndex = 2
			})
            local value15_102 = t1.value15
            local uDim2_174 = UDim2.new(1, -24, 0, 0)
            local uDim2_175 = UDim2.new(0, 12, 1, -10)
            local vector2_60 = Vector2.new(0, 1)
            local t71 = {
				Size = uDim2_174,
				AutomaticSize = "Y",
				Position = uDim2_175,
				AnchorPoint = vector2_60,
				BackgroundTransparency = 1,
				ZIndex = 3
			}
            local value15_103 = t1.value15
            local uDim27 = UDim.new(0, 2)
            local v1350 = value15_102("Frame", v1329, t71, { value15_103("UIListLayout", {
				SortOrder = "LayoutOrder",
				Padding = uDim27
			}) })
      local value15_104 = t1.value15
            local uDim2_176 = UDim2.new(1, 0, 0, 18)
            local GothamBold = Enum.Font.GothamBold
            local color3_55 = Color3.fromRGB(255, 255, 255)
            local v1355 = value15_104("TextLabel", v1350, {
				Size = uDim2_176,
				BackgroundTransparency = 1,
				Font = GothamBold,
				TextColor3 = color3_55,
				TextXAlignment = "Left",
				TextTruncate = "AtEnd",
				TextSize = 15,
				Text = p329Title,
				LayoutOrder = 1
			})
            local value15_105 = t1.value15
            local uDim2_177 = UDim2.new(1, 0, 0, 0)
            local Gotham3 = Enum.Font.Gotham
            local color3_56 = Color3.fromRGB(220, 220, 220)
            local v1360 = value15_105("TextLabel", v1350, {
				Size = uDim2_177,
				AutomaticSize = "Y",
				BackgroundTransparency = 1,
				Font = Gotham3,
				TextColor3 = color3_56,
				TextXAlignment = "Left",
				TextWrapped = true,
				TextSize = 11,
				Text = Description,
				LayoutOrder = 2
			})

            v1324.MouseEnter:Connect(function()
                t1.value29({
					v1342,
					"BackgroundTransparency",
					0.15,
					0.2
				})
            end)
            v1324.MouseLeave:Connect(function()
                t1.value29({
					v1342,
					"BackgroundTransparency",
					0.35,
					0.2
				})
            end)
            v1324.Activated:Connect(function()
                t1.value26()
                t1.value16:FireCallback(Callback)
            end)

            return {
				Visible = function(_, ...)
                t1.value16:ToggleVisible(v1324, ...)
            end,
				Destroy = function(_)
                v1324:Destroy()
            end,
				Callback = function(_, ...)
                t1.value16:InsertCallback(Callback, ...)
            end,
				Set = function(_, p334, p335, p336)
                if type(p334) == "string" then
                    v1355.Text = p334
                end

                if type(p335) == "string" then
                    v1360.Text = p335
                end

                if type(p336) == "string" then
                    v1338.Image = t1.value7:GetIcon(p336)
                end
            end,
				SetScaleType = function(_, p338)
                if t70[p338] then
                    v1338.ScaleType = t70[p338]
                end
            end
			}
        end

        return t33
    end
    v332.Activated:Connect(t12.value49.CloseBtn)
    t12.value44.Activated:Connect(t12.value49.MinimizeBtn)

    return t12.value49
end
return t1.value7
