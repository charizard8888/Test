# Istor

## Yddraig
Dex: 10001 
![Dragon Type](http://play.pokemonshowdown.com/sprites/types/Dragon.png)	

| HP | Atk | Def | SpA | SpD | Spe |
|----|-----|-----|-----|-----|-----|
| 60 | 60  | 55  | 75  | 55  | 85  |

Abilities: Infernal Scales, Shed Skin<br/>
Infernal Scales: This Pokemon's Water power is 2x; it can't be burned; Fire power against it is halved.<br/>
Height: 1.1 m Weight: 23 Kg	Color: Red	Egg Groups: Dragon<br/>
### Learnset:	
Inferno     
Outrage      
Tackle     
Ember	
Tail Whip     
Twister     
Endeavor     
Defog     
Headbutt     
Aircutter     
Dragonbreath     
Roar     
Flamecharge      
Dragondance     
Boomburst     
Dragonrush     
Doubleteam      
Clangingscales     
Dragonpulse     
Wideguard     
Overheat     
Dracometeor     
Workup     
Dragonclaw     
Calmmind     
Roar     
Toxic     
Bulkup     
Hiddenpower     
Sunnyday     
Taunt     
Hyperbeam     
Lightscreen     
Protect     
Roost     
Safeguard     
Frustration    
Solarbeam    
Thunderbolt     
Thunder     
Return     
Brickbreak     
Reflect     
Flamethrower     
Firebast     
Aerialace     
Torment     
Facade     
Rest     
Attract     
Round     
Echoedvoice     
Steelwing     
Roost     
Skydrop     
Brutalswing     
Acrobatics     
Shadowclaw     
Payback     
Gigaimpact     
Thunderwave     
Swordsdance     
Fly     
Bulldoze     
Dragontail    
Infestation     
Poisonjab     
Swagger     
Sleeptalk     
Uturn     
Substitute     
Wildcharge     
Snarl    
Naturepower     
Darkpulse    
Confide     	
##  Detuoy: 
	      	Dex: 10002
	      	species: "Detuoy",
	      	types: ["Steel", "Flying"],
		      baseStats: {hp: 60, atk: 120, def: 150, spa: 30, spd: 120, spe: 30},
	      	abilities: {0: "Aerilate"},
	      	heightm: 1.8,
	      	weightkg: 666,
	      	color: "Gray",
	      	eggGroups: ["Mineral"],
    	},
	mycelore: {
		num: 10003,
		species: "Mycelore",
		types: ["Poison", "Fairy"],
		baseStats: {hp: 45, atk: 31, def: 21, spa: 86, spd: 106, spe: 31},
		abilities: {0: "Serene Grace", 1: "Effect Spore", H: "Wonder Skin"},
		heightm: 0.2,
		weightkg: 3.2,
		color: "Purple",
		evos: ["Muceptio"],
		eggGroups: ["Grass", "Amorphous"],
	},
	muceptio: {
		num: 10004,
		species: "Muceptio",
		types: ["Poison", "Fairy"],
		baseStats: {hp: 60, atk: 46, def: 36, spa: 101, spd: 121, spe: 61},
		abilities: {0: "Serene Grace", 1: "Effect Spore", H: "Wonder Skin"},
		heightm: 0.6,
		weightkg: 9.8,
		color: "Purple",
		prevo: "mycelore",
		evos: ["Malifery"],
		eggGroups: ["Grass", "Amorphous"],
	},
	malifery: {
		num: 10005,
		species: "Malifery",
		types: ["Poison", "Fairy"],
		baseStats: {hp: 75, atk: 61, def: 51, spa: 116, spd: 136, spe: 91},
		abilities: {0: "Serene Grace", 1: "Effect Spore", H: "Wonder Skin"},
		heightm: 1.6,
		weightkg: 23.8,
		color: "Purple",
		prevo: "muceptio",
		eggGroups: ["Grass", "Amorphous"],
	},
	canos: {
		num: 10006,
		species: "Canos",
		types: ["Normal"],
		baseStats: {hp: 35, atk: 50, def: 30, spa: 35, spd: 40, spe: 40},
		abilities: {0: "Run Away", 1: "Quick Feet", H: "Pick Up"},
		heightm: 0.5,
		weightkg: 6.8,
		color: "Brown",
		evos: ["Mortos"],
		eggGroups: ["Field"],
	},
	mortos: {
		num: 10007,
		species: "Mortos",
		types: ["Normal", "Ghost"],
		baseStats: {hp: 70, atk: 100, def: 60, spa: 70, spd: 80, spe: 80},
		abilities: {0: "Run Away", 1: "Quick Feet", H: "Pick Up"},
		heightm: 1.0,
		weightkg: 20.2,
		color: "Gray",
		prevo: "canos",
		eggGroups: ["Field"],
	},
	
	/* Istori Forms */
	
	doduo: {
		num: 84,
		species: "Doduo",
		types: ["Normal", "Flying"],
		baseStats: {hp: 35, atk: 85, def: 45, spa: 35, spd: 35, spe: 75},
		abilities: {0: "Run Away", 1: "Early Bird", H: "Tangled Feet"},
		heightm: 1.4,
		weightkg: 39.2,
		color: "Brown",
		evos: ["dodrio"],
		eggGroups: ["Flying"],
		otherFormes: ["doduoistor"],
	},
	dodrio: {
		num: 85,
		species: "Dodrio",
		types: ["Normal", "Flying"],
		baseStats: {hp: 60, atk: 110, def: 70, spa: 60, spd: 60, spe: 110},
		abilities: {0: "Run Away", 1: "Early Bird", H: "Tangled Feet"},
		heightm: 1.8,
		weightkg: 85.2,
		color: "Brown",
		prevo: "doduo",
		evoLevel: 31,
		eggGroups: ["Flying"],
		otherFormes: ["dodrioistor"],
	},
	"impalingfeather": {
		num: 10001,
		accuracy: 100,
		basePower: 85,
		category: "Physical",
		desc: "Has a 20% chance to lower the target's Defense by 1 stage.",
		shortDesc: "20% chance to lower the target's Defense by 1.",
		id: "impalingfeather",
		isViable: true,
		name: "impalingfeather",
		pp: 10,
		priority: 0,
		flags: {protect: 1, mirror: 1},
		secondary: {
			chance: 20,
			boosts: {
				def: -1,
			},
		},
		target: "normal",
		type: "Steel",
		zMovePower: 160,
		contestType: "Cool",
	},
};
	doduoistor: {
		num: 84,
		species: "Doduo-Istor",
		types: ["Steel", "Flying"],
		baseStats: {hp: 35, atk: 85, def: 45, spa: 35, spd: 35, spe: 75},
		abilities: {0: "Pressure", 1: "Early Bird", H: "Tangled Feet"},
		heightm: 1.4,
		weightkg: 39.2,
		color: "Brown",
		evos: ["dodrioistor"],
		eggGroups: ["Flying"],
	},
	dodrioistor: {
		num: 85,
		species: "Dodrio-Istor",
		types: ["Steel", "Flying"],
		baseStats: {hp: 60, atk: 110, def: 70, spa: 60, spd: 60, spe: 110},
		abilities: {0: "Pressure", 1: "Early Bird", H: "Tangled Feet"},
		heightm: 1.8,
		weightkg: 85.2,
		color: "Brown",
		prevo: "doduoistor",
		evoLevel: 31,
		eggGroups: ["Flying"],



# Learnsets
	detuoy: { learnset: {
		explosion: ["7L1"],
	}},
	mycelore: {learnset: {
		acid: ["7L1"],
		fairywind: ["7L1"],
		absorb: ["7L4"],
		leechseed: ["7L7"],
		sludge: ["7L12"],
		ingrain: ["7L15"],
		megadrain: ["7L18"],
		acidspray: ["7L23"],
		toxic: ["7L26"],
		gigadrain: ["7L29"],
		toxicspikes: ["7L34"],
		moonblast: ["7L37"],
		venomdrench: ["7L40"],
		spore: ["7L45"],
		acidarmor: ["7E"],
		mistyterrain: ["7E"],
		aromatherapy: ["7E"],
		dazzlinggleam: ["7E", "7M"],
		aromaticmist: ["7E"],
		moonlight: ["7E"],
		calmmind: ["7M"],
		toxic: ["7M"],
		venoshock: ["7M"],
		hiddenpower: ["7M"],
		taunt: ["7M"],
		lightscreen: ["7M"],
		protect: ["7M"],
		raindance: ["7M"],
		safeguard: ["7M"],
		frustration: ["7M"],
		solarbeam: ["7M"],
		return: ["7M"],
		psychic: ["7M"],
		shadowball: ["7M"],
		doubleteam: ["7M"],
		sludgewave: ["7M"],
		sludgebomb: ["7M"],
		torment: ["7M"],
		facade: ["7M"],
		rest: ["7M"],
		attract: ["7M"],
		thief: ["7M"],
		round: ["7M"],
		echoedvoice: ["7M"],
		energyball: ["7M"],
		thunderwave: ["7M"],
		psychup: ["7M"],
		infestation: ["7M"],
		poisonjab: ["7M"],
		dreameater: ["7M"],
		grassknot: ["7M"],
		swagger: ["7M"],
		sleeptalk: ["7M"],
		substitute: ["7M"],
		trickroom: ["7M"],
		naturepower: ["7M"],
		darkpulse: ["7M"],
		confide: ["7M"],
	}},
	muceptio: {learnset: {
		acid: ["7L1"],
		fairywind: ["7L1"],
		absorb: ["7L4"],
		leechseed: ["7L9"],
		sludge: ["7L14"],
		ingrain: ["7L17"],
		megadrain: ["7L22"],
		acidspray: ["7L27"],
		toxic: ["7L30"],
		gigadrain: ["7L35"],
		toxicspikes: ["7L40"],
		moonblast: ["7L43"],
		venomdrench: ["7L48"],
		spore: ["7L53"],
		acidarmor: ["7E"],
		mistyterrain: ["7E"],
		aromatherapy: ["7E"],
		dazzlinggleam: ["7E", "7M"],
		aromaticmist: ["7E"],
		moonlight: ["7E"],
		calmmind: ["7M"],
		toxic: ["7M"],
		venoshock: ["7M"],
		hiddenpower: ["7M"],
		taunt: ["7M"],
		lightscreen: ["7M"],
		protect: ["7M"],
		raindance: ["7M"],
		safeguard: ["7M"],
		frustration: ["7M"],
		solarbeam: ["7M"],
		return: ["7M"],
		psychic: ["7M"],
		shadowball: ["7M"],
		doubleteam: ["7M"],
		sludgewave: ["7M"],
		sludgebomb: ["7M"],
		torment: ["7M"],
		facade: ["7M"],
		rest: ["7M"],
		attract: ["7M"],
		thief: ["7M"],
		round: ["7M"],
		echoedvoice: ["7M"],
		energyball: ["7M"],
		thunderwave: ["7M"],
		psychup: ["7M"],
		infestation: ["7M"],
		poisonjab: ["7M"],
		dreameater: ["7M"],
		grassknot: ["7M"],
		swagger: ["7M"],
		sleeptalk: ["7M"],
		substitute: ["7M"],
		trickroom: ["7M"],
		naturepower: ["7M"],
		darkpulse: ["7M"],
		confide: ["7M"],
	}},
	malifery: {learnset: {
		fairywind: ["7L1"],
		sludge: ["7L1"],
		moonblast: ["7L1"],
		spore: ["7L1"],
		acidarmor: ["7E"],
		mistyterrain: ["7E"],
		aromatherapy: ["7E"],
		dazzlinggleam: ["7E", "7M"],
		aromaticmist: ["7L1", "7E"],
		moonlight: ["7L1", "7E"],
		calmmind: ["7M"],
		toxic: ["7M"],
		venoshock: ["7M"],
		hiddenpower: ["7M"],
		taunt: ["7M"],
		lightscreen: ["7M"],
		protect: ["7M"],
		raindance: ["7M"],
		safeguard: ["7M"],
		frustration: ["7M"],
		solarbeam: ["7M"],
		return: ["7M"],
		psychic: ["7M"],
		shadowball: ["7M"],
		doubleteam: ["7M"],
		sludgewave: ["7M"],
		sludgebomb: ["7M"],
		torment: ["7M"],
		facade: ["7M"],
		rest: ["7M"],
		attract: ["7M"],
		thief: ["7M"],
		round: ["7M"],
		echoedvoice: ["7M"],
		energyball: ["7M"],
		thunderwave: ["7M"],
		psychup: ["7M"],
		infestation: ["7M"],
		poisonjab: ["7M"],
		dreameater: ["7M"],
		grassknot: ["7M"],
		swagger: ["7M"],
		sleeptalk: ["7M"],
		substitute: ["7M"],
		trickroom: ["7M"],
		naturepower: ["7M"],
		darkpulse: ["7M"],
		confide: ["7M"],
		thunderbolt: ["7M"],
		thunder: ["7M"],
		hyperbeam: ["7M"],
		gigaimpact: ["7M"],
	}},
	doduoistor: {learnset: {
		acupressure: ["7L33"],
		aerialace: ["7M"],
		agility: ["7L26"],
		assurance: ["7E"],
		attract: ["7M"],
		bravebird: ["7E"],
		confide: ["7M"],
		doublehit: ["7L22"],
		doubleteam: ["7M"],
		drillpeck: ["7L43"],
		echoedvoice: ["7M"],
		endeavor: ["7L47", "7E"],
		facade: ["7M"],
		feintattack: ["7E"],
		flail: ["7E"],
		flashcannon: ["7M"],
		fly: ["7M"],
		frustration: ["7M"],
		furyattack: ["7L12"],
		growl: ["7L1"],
		hiddenpower: ["7M"],
		irondefense: ["7E"],
		ironhead: ["7E"],
		jumpkick: ["7L40"],
		mirrormove: ["7E"],
		naturalgift: ["7E"],
		peck: ["7L1"],
		pluck: ["7L19"],
		protect: ["7M"],
		pursuit: ["7L15"],
		quickattack: ["7L5"],
		rest: ["7M"],
		return: ["7M"],
		roost: ["7M"],
		round: ["7M"],
		sleeptalk: ["7M"],
		steelwing: ["7M", "7L9"],
		smartstrike: ["7M"],
		substitute: ["7M"],
		sunnyday: ["7M"],
		swagger: ["7M"],
		swordsdance: ["7M", "7L36"],
		thief: ["7M"],
		impalingfeather: ["7L50"],
		toxic: ["7M"],
		heavyslam: ["7L29"],
		workup: ["7M"],
	}},
	dodrioistor: {learnset: {
		acupressure: ["7L34"],
		aerialace: ["7M"],
		agility: ["7L260"],
		assurance: ["7E"],
		attract: ["7M"],
		bravebird: ["7E"],
		confide: ["7M"],
		doublehit: ["7L22"],
		doubleteam: ["7M"],
		drillpeck: ["7L47"],
		echoedvoice: ["7M"],
		endeavor: ["7L52", "7E"],
		facade: ["7M"],
		feintattack: ["7E"],
		flail: ["7E"],
		flashcannon: ["7M"],
		fly: ["7M"],
		frustration: ["7M"],
		furyattack: ["7L121"],
		gigaimpact: ["7M"],
		growl: ["7L1"],
		hiddenpower: ["7M"],
		hyperbeam: ["7M"],
		irondefense: ["7E"],
		ironhead: ["7E"],
		jumpkick: ["7L43"],
		mirrormove: ["7E"],
		naturalgift: ["7E"],
		payback: ["7M"],
		peck: ["7L1"],
		pluck: ["7L19"],
		protect: ["7M"],
		pursuit: ["7L15"],
		quickattack: ["7L5", "7E", "7L1"],
		rest: ["7M"],
		return: ["7M"],
		roost: ["7M"],
		round: ["7M"],
		sleeptalk: ["7M"],
		smartstrike: ["7M"],
		steelwing: ["7M", "7L8", "7L1"],
		substitute: ["7M"],
		sunnyday: ["7M"],
		supersonic: ["7E"],
		swagger: ["7M"],
		swordsdance: ["7M", "7L38"],
		taunt: ["7M"],
		thief: ["7M"],
		impalingfeather: ["7L56"],
		torment: ["7M"],
		toxic: ["7M"],
		triattack: ["7L1"],
		heavyslam: ["7L29"],
		workup: ["7M"],
