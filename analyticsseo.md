# AnalyticsSEO

Analytisc SEO is a tool used for getting keyword rankings

#### Available methods

* serps POST
* serps  GET

## [POST] serps POST



#### Description

* **Method:** POST
* **URL:** /serps/

#### Query parameters

*No query parameters accepted.*

#### Body payload

```json
{
    "search_engine": "google",
    "region": "global",
    "language": "en",
    "max_results": 100,
    "phrase": "How good is your SEO"
}
```

#### Example responses

*No example responses saved.*

## [GET] serps  GET



#### Description

* **Method:** GET
* **URL:** /serps/737c1983-a0ba-4058-9f25-6baee3e57ca3

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

##### serps - vacation in spain - country - gb

```json
{
    "jid": "a3634d7f-32bf-47cf-97ce-e3d1f01a7808",
    "ready": true,
    "request": {
        "jid": "a3634d7f-32bf-47cf-97ce-e3d1f01a7808",
        "language": "en",
        "max_results": 100,
        "parameters": {
            "full_pages_count": 3
        },
        "phrase": "vacation in spain",
        "region": "gb",
        "search_engine": "google",
        "search_type": "country",
        "strategy": "standard",
        "town": null,
        "universal": 1,
        "user_agent": "pc"
    },
    "response": {
        "results": {
            "ad": {
                "1": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "2": {
                    "description": "Private customized tours with driver guides",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Barcelona shore trips - bestprivatetours.com‎",
                    "type": "ad",
                    "url": "http://www.bestprivatetours.com/"
                },
                "3": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday - Zwerfdierenindahab.nl‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "4": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "5": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "6": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "7": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "8": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "9": {
                    "description": "Ilusiones como tratamiento de vida para niños con enfermedades graves",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "10": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "11": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "12": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "13": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "14": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "15": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "16": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "17": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "18": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "19": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "20": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "21": {
                    "description": "Villa rentals in Costa Brava, Costa Dorada & Barcelona. Book now!",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Holiday villas in Spain - catalanholidays.com‎",
                    "type": "ad",
                    "url": "http://www.catalanholidays.com/listar.php?TipoGestion=A&TipoInmueble=-1&lang=en&country=ESP"
                },
                "22": {
                    "description": "Rental Marketplace. Owners Direct!",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Spain Holiday Rental - Long & Short Term - Furn & Unfurn‎",
                    "type": "ad",
                    "url": "https://www.sublet.com/State_Rentals/Spain_Rentals.asp?source=10140"
                },
                "23": {
                    "description": "Explore the wonders of Rwanda Culture, Community & Wild Life",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "A Holiday of a Life Time‎",
                    "type": "ad",
                    "url": "http://azizilife.com/get-involved/experiences"
                },
                "24": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "25": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "26": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "27": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "28": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "29": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "30": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                }
            },
            "image": {
                "1": {
                    "description": "",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "http://vacationclub.silverpoint.com/english/silverpoint/spain.aspx",
                    "type": "image",
                    "url": "http://vacationclub.silverpoint.com/english/silverpoint/spain.aspx"
                },
                "2": {
                    "description": "",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "http://blog.visafirst.com/europe-by-road-the-5-best-european-driving-vacation-routes/",
                    "type": "image",
                    "url": "http://blog.visafirst.com/europe-by-road-the-5-best-european-driving-vacation-routes/"
                },
                "3": {
                    "description": "",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "https://www.expedia.co.uk/Barcelona.d179992.Holidays-City-Breaks",
                    "type": "image",
                    "url": "https://www.expedia.co.uk/Barcelona.d179992.Holidays-City-Breaks"
                },
                "4": {
                    "description": "",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "http://www.vacation-key.com/spain",
                    "type": "image",
                    "url": "http://www.vacation-key.com/spain"
                }
            },
            "news": {},
            "organic": {
                "1": {
                    "description": "Offers vacation rentals and accommodations in touristic regions. Apartments, villas and townhouses booked directly with the property owners.",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [
                        {
                            "links": [
                                {
                                    "title": "Costa del Sol",
                                    "description": "",
                                    "url": "http://www.spain-holiday.com/Costa-del-Sol/holiday-rentals"
                                },
                                {
                                    "title": "Spain",
                                    "description": "",
                                    "url": "http://www.spain-holiday.com/Spain/holiday-rentals"
                                },
                                {
                                    "title": "Costa Blanca",
                                    "description": "",
                                    "url": "http://www.spain-holiday.com/Costa-Blanca/holiday-rentals"
                                },
                                {
                                    "title": "Beach villas for rent in Spain ...",
                                    "description": "",
                                    "url": "http://www.spain-holiday.com/Spain/holiday-rentals/beach"
                                }
                            ],
                            "type": "site_links"
                        }
                    ],
                    "title": "Spain Holiday - Holiday villas, apartments and cottages for ...",
                    "type": "organic",
                    "url": "http://www.spain-holiday.com/"
                },
                "2": {
                    "description": "Vacation Villas - your answer to finding the perfect holiday home to rent or to buy on the Costa Blanca in Spain. We have the finest selection of properties to rent ...",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Costa Blanca, Spain Villa Rentals - rent in Javea and Denia",
                    "type": "organic",
                    "url": "http://www.vacationvillasspain.com/"
                },
                "3": {
                    "description": "Spain Holidays: Find Spain holiday packages and city breaks to Spain on TripAdvisor by comparing prices and reading Spain hotel ... 1. Barcelona Vacations.",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "The Best Spain Holidays 2016 - TripAdvisor",
                    "type": "organic",
                    "url": "https://www.tripadvisor.co.uk/Vacation_Packages-g187427-Spain-Vacations.html"
                },
                "4": {
                    "description": "Spain Tourism: TripAdvisor has 9717503 reviews of Spain Hotels, Attractions, and Restaurants making it your best Spain resource.",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Spain Tourism: Best of Spain - TripAdvisor",
                    "type": "organic",
                    "url": "https://www.tripadvisor.co.uk/Tourism-g187427-Spain-Vacations.html"
                },
                "5": {
                    "description": "5 Jan 2016 - Our experts' pick of the top 10 beach and seaside holidays in Spain for 2016, including the best beaches for watersports, families and ...",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "The top 10 beach holidays in Spain - Telegraph",
                    "type": "organic",
                    "url": "http://www.telegraph.co.uk/travel/destinations/europe/spain/articles/The-top-10-beach-holidays-in-Spain/"
                },
                "6": {
                    "description": "9 Jul 2014 - From a cottage in the mountains to stylish pads in Seville and Barcelona, we select the best self-catering properties in Spain to keep the kids ...",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.theguardian.com › Travel › Spain holidays"
                        }
                    ],
                    "title": "10 of the best family self-catering holidays in Spain | Travel ...",
                    "type": "organic",
                    "url": "http://www.theguardian.com/travel/2014/jul/09/10-best-self-catering-holidays-spain"
                },
                "7": {
                    "description": "Villa, finca, townhouse, apartment or new-build properties for sale in and around Javea and Denia, Costa Blanca, Spain. Investment properties too.",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Vacation Villas Properties for sale in Javea and Denia, Spain",
                    "type": "organic",
                    "url": "http://www.vacationvillassales.com/"
                },
                "8": {
                    "description": "Holiday in the sun: 2.100 holiday houses and holiday flats in Spain, on Majorca or the Canary Islands, in Andalusia, Catalonia or on the Costa Blanca. ¡Vamos!",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.vacation-apartments.com › Europe"
                        },
                        {
                            "guessed_type": "review",
                            "type": "rating",
                            "votes": 1600,
                            "score": 4.9,
                            "raw": " Rating: 4.9 - ‎1,600 votes"
                        }
                    ],
                    "title": "holiday houses and holiday flats Spain - Vacation in Spain",
                    "type": "organic",
                    "url": "http://www.vacation-apartments.com/europe/spain/"
                },
                "9": {
                    "description": "10+ items - Vacation Rentals in Spain. Here you find 4395 vacation rentals, ...",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Vacation Rentals Spain Vacation Rental Spain Rent Holiday ...",
                    "type": "organic",
                    "url": "http://www.rent-holiday-homes.com/Vacation-Rentals-Spain-c192_p1.html"
                },
                "10": {
                    "description": "Paradores Spain Special Offers - Great Selection of discounted 7 night Parador tours with routes all over Spain. Book early for best offers.",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Paradores Special Offers - Spain Vacation Tours Packages ...",
                    "type": "organic",
                    "url": "http://www.totallyspain.com/spain_travel_offers.asp"
                },
                "11": {
                    "description": "This is also a top location for winter vacations with tourists trying to escape the colder months, as the south of Spain, in particular the coast of Andalusia, is often ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.casamundo.co.uk › Holiday lettings"
                        },
                        {
                            "guessed_type": "review",
                            "type": "rating",
                            "votes": 14340,
                            "score": 4.1,
                            "raw": " Rating: 4.1 - ‎14,340 votes"
                        }
                    ],
                    "title": "Book holiday homes in Spain online with CASAMUNDO",
                    "type": "organic",
                    "url": "http://www.casamundo.co.uk/holiday-rentals/spain"
                },
                "12": {
                    "description": "Find the best surfing locations in Spain at Errant Surf. ... We provide some of the best surfing holidays and surf vacations in Spain and have done so since 2005.",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Spain - Errant Surf",
                    "type": "organic",
                    "url": "https://www.errantsurf.com/locations/World-Europe-Spain"
                },
                "13": {
                    "description": "Marriott's Marbella Beach Resort Marriott Vacation Club Exchange Resort. Urb. Marbella del Este, Crta. de Cádiz, Km 193, 29604 Marbella, Costa del Sol, Spain",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Marriott's Marbella Beach Resort - Marriott Vacation Club ...",
                    "type": "organic",
                    "url": "http://www.marriottvacationclub.com/vacation-resorts/marriott-marbella-beach-club/overview.shtml"
                },
                "14": {
                    "description": "They are ideal for a wonderful holiday or short vacation in Spain with the family. Many houses have space for 2 or 3 families. There are also spacious villa ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Spain Holiday rentals, villa rentals, Spain vacation self ...",
                    "type": "organic",
                    "url": "http://www.cottage-rental.com/spain-holiday-rentals.asp"
                },
                "15": {
                    "description": "Villa Rentals Spain & Villa Rentals Italy from El Sol Villa Specialists. We provide the best luxury vacation rentals in Spain, France, Italy & worldwide.",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "El Sol Villas: Luxury Villa Rentals | Vacation Home Rentals",
                    "type": "organic",
                    "url": "http://www.elsolvillas.com/"
                },
                "16": {
                    "description": "Find a Marriott Vacation Club hotel in Spain offering accommodation for business & leisure travellers. Hotels in Spain offering quality service & facilities at ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Marriott Vacation Club Hotels, Spain. Choose a hotel at ...",
                    "type": "organic",
                    "url": "http://www.marriott.co.uk/hotel-search/spain.hotels.marriott-vacation-club-international/"
                },
                "17": {
                    "description": "Totally Spain is a savvy and reputable Spain & Portugal Travel Agency dedicated to organising exceptional Custom Designed Private Travel, Tours & Vacations ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Totally Spain: Spain Travel - Travel Agent - Spain Tour",
                    "type": "organic",
                    "url": "http://www.totallyspain.com/"
                },
                "18": {
                    "description": "Find all inclusive holidays in Spain with easyJet holidays. With great all inclusive deals to top Spanish destinations such as Tenerife and Majorca, you can get ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Spain All Inclusive Holidays | easyJet holidays",
                    "type": "organic",
                    "url": "http://www.easyjet.com/en/holidays/events/spain-all-inclusive/"
                },
                "19": {
                    "description": "13 Aug 2015 - Take a break from your old Costas favourite to spread your towel on our choice of the 10 absolute best beaches in Spain - a country with more ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.mirror.co.uk › Lifestyle › Travel › Spain holidays"
                        }
                    ],
                    "title": "Top 10 guide to the best beaches in Spain - Mirror Online",
                    "type": "organic",
                    "url": "http://www.mirror.co.uk/lifestyle/travel/top-ten-spain-best-beaches-402325"
                },
                "20": {
                    "description": "The Ebro Delta, or Delta de L'Ebre, is one of the best bird watching sites in Europe - easily on a par with the Coto Doñana and the Camargue - and without doubt ...",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "birding holidays vacations in Spain EBRO DELTA euro trip ...",
                    "type": "organic",
                    "url": "http://www.catalanbirdtours.com/Spain birding/EBRO birdwatching tours.html"
                },
                "21": {
                    "description": "Independent Bike Vacation in Spain – Route of the Caliphate ... This biking vacation in Andalucia is available as a self guided cycle tour which we have graded ...",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Route Caliphate Bike Vacation Tour in Spain",
                    "type": "organic",
                    "url": "http://www.hookedoncycling.co.uk/spain-route-of-the-caliphate/"
                },
                "22": {
                    "description": "Spain Villa Vacation Rentals,Holiday Home, Bed & Breakfast BNB B&B Luxury Properties, Apartment Rental in Andalusia, Costa del Sol, direct by owner or ...",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Spain Villa Vacation Rentals Spain Holiday Home Bed ...",
                    "type": "organic",
                    "url": "http://www.vacation-key.com/spain"
                },
                "23": {
                    "description": "Welcome To Miraflores Vacation Properties ... Miraflores, an award-winning luxury resort of quality residential properties and vacation homes in Southern Spain.",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Miraflores: Award-Winning Luxury Development Resort ...",
                    "type": "organic",
                    "url": "http://www.miraflores.com/"
                },
                "24": {
                    "description": "Andalucia Rentals specialising in long rentals in the provinces of Andalucia, Southern Spain.",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Andalucia Rentals - long term rentals - and holiday lets in ...",
                    "type": "organic",
                    "url": "http://www.andaluciarentals.com/"
                },
                "25": {
                    "description": "Unique villas in Spain with private pools, all handpicked by own experts! Book your family holiday in Spain directly from the owners!",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Villas in Spain | Holiday Rentals in Spain | Oliver's Travels",
                    "type": "organic",
                    "url": "http://www.oliverstravels.com/spain/"
                },
                "26": {
                    "description": "Find your perfect property in Spain, search a wide range of properties for sale in Spain with Rightmove.",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Property for sale in Spain - Spanish Property for Sale",
                    "type": "organic",
                    "url": "http://www.rightmove.co.uk/overseas-property/in-Spain.html"
                },
                "27": {
                    "description": "Just a 2 and a half hour flight and you can be enjoying golf in the sunshine!",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "All Inclusive golf holidays in Spain - Premier Iberian Golf ...",
                    "type": "organic",
                    "url": "http://www.premieriberian.com/golf_holiday_filtered.aspx?area=41&name=Spain&filter=16"
                },
                "28": {
                    "description": "Spain or Thailand, Which Vacation Destination is Cheaper – You Might Be Surprised. May 28, 2011. When I was a kid, Spain was the preferred holiday ...",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Spain or Thailand, Which Vacation Destination is Cheaper ...",
                    "type": "organic",
                    "url": "http://seriouslyspain.com/spain-or-thailand-which-vacation-destination-is-cheaper-you-might-be-surprised"
                },
                "29": {
                    "description": "Planning to spend cheap holiday in Spain 2016? Here are a lot of tours and discount vacation packages to Spain. Check prices and choose your trip with ...",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Holidays in Spain 2016: discount prices, vacation packages ...",
                    "type": "organic",
                    "url": "http://tripvariator.co.uk/spain/"
                },
                "30": {
                    "description": "Whether you are looking for guided or self-guided wine tours to Spain´s wine regions, short gastronomic getaways, a roadtrip or long vacations with cultural ...",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Wine Tours in Spain by winetourismspain.com",
                    "type": "organic",
                    "url": "http://winetourismspain.com/"
                },
                "31": {
                    "description": "9140 Spain vacation homes. Good availability and great rates for vacation homes in Spain. Read reviews and choose the best vacation home for your vacation.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Booking.com : Spain vacation homes. 9140 vacation homes ...",
                    "type": "organic",
                    "url": "http://www.booking.com/holiday-homes/country/es.html"
                },
                "32": {
                    "description": "Horse riding is deeply ingrained into Spanish culture and there are many equestrian vacations in Spain to choose from. With a combination of quality horses, ...",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Riding Holidays in Spain - In The Saddle",
                    "type": "organic",
                    "url": "https://www.inthesaddle.com/rides/search/spain"
                },
                "33": {
                    "description": "Spain offers spectacular countryside, much of which is totally unspoilt. ... Riding holidays and vacations overview. Riding ... Horse Riding Holidays, Spain.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.farandride.com › Riding Holidays"
                        }
                    ],
                    "title": "Horse riding holidays in Spain (11 destinations) - Far and Ride",
                    "type": "organic",
                    "url": "http://www.farandride.com/riding-holidays/spain/"
                },
                "34": {
                    "description": "Vacation Ownership Specials - Take advantage of timeshare offers at resort destinations worldwide – each ... Marriott's Marbella Beach ResortMarbella, Spain.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Marriott's Marbella Beach Resort - Marriott Vacation Club",
                    "type": "organic",
                    "url": "http://www.marriottvacationclub.eu/european-resorts/marbella/"
                },
                "35": {
                    "description": "Ronda is an excellent base for the independent traveller to explore Andalucia, a beautiful part of Southern Spain - your ideal summer vacation destination.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Holiday Villas Andalucia | Luxury Villas to Rent | Holidays ...",
                    "type": "organic",
                    "url": "http://www.real-ronda.com/"
                },
                "36": {
                    "description": "25 Jul 2015 - Comprehensive travel, vacation, lodging & tourism guide to Spain.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Spanish Holiday - Vacation in Spain - Travel ...",
                    "type": "organic",
                    "url": "http://www.allspainaccommodation.com/"
                },
                "37": {
                    "description": "22 May 2015 - Superhero's day off! Arrow star Stephen Amell goes shirtless as he and his bikini-clad wife enjoy a vacation in Marbella, Spain on Thursday.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Arrow star Stephen Amell goes shirtless on vacation",
                    "type": "organic",
                    "url": "http://www.dailymail.co.uk/tvshowbiz/article-3093279/Arrow-star-Stephen-Amell-goes-shirtless-bikini-clad-wife-enjoy-vacation-Spain.html"
                },
                "38": {
                    "description": "Horse Riding Holidays. Riding Holidays Spain. Andalucia Short Stay · Andalucia One Week · Barcelona/Costa Brava · Madrid · Mallorca. Riding Holidays UK.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Spanish Riding Holiday | Equestrian Vacation Malaga ...",
                    "type": "organic",
                    "url": "http://www.equestrian-escapes.com/riding-holidays-Spain-luxury/"
                },
                "39": {
                    "description": "... and apartment accommodation in Barcelona for your holiday rental in Spain from ... Fully Renovated Building with Vacation Rentals Apartments - Sant Pau 1 ...",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.ownersdirect.co.uk › ... › Spain › Catalonia › Barcelona Province"
                        },
                        {
                            "guessed_type": "review",
                            "type": "rating",
                            "votes": 152,
                            "score": 4.5,
                            "raw": " Rating: 4.5 - ‎152 reviews - ‎Starting from £64.20"
                        }
                    ],
                    "title": "Apartments in Barcelona - Self Catering Barcelona",
                    "type": "organic",
                    "url": "https://www.ownersdirect.co.uk/rentals/spain/barcelona/r991"
                },
                "40": {
                    "description": "Spain Holiday Rentals - Find wonderful and unique local holiday rentals in Spain ... Marvelous Golf Course View - Vacation Townhouse in La Torre Golf Resort.",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Spain Holiday Rentals: Spain Holiday Apartment, Home and ...",
                    "type": "organic",
                    "url": "http://www.alwaysonvacation.co.uk/holiday-rentals/spain/nnes"
                },
                "41": {
                    "description": "Spain is surely worth a vacation or even a business or short holiday trip, as the country is diverse in many ways, from language and people to climate, landscape ...",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Accommodation and travel guide for Spain holiday and events",
                    "type": "organic",
                    "url": "http://www.spaindreams.com/"
                },
                "42": {
                    "description": "24 Nov 2014 - These Thrasher vacation edits are kicking off! Watch below to see the Spanish edition of their venture and to witness some quality lurking from ...",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Thrasher Vacation: Spain - Sidewalk Skateboarding",
                    "type": "organic",
                    "url": "http://sidewalkmag.com/skateboard-news/thrasher-vacation-spain.html"
                },
                "43": {
                    "description": "Entire home/flat for £36. The house provides: 115m2 inside,180m2 outside,wifi,TV 3D,grill,",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.airbnb.co.uk › Spain › Comunidad Valenciana › Busot"
                        }
                    ],
                    "title": "Beautiful vacation home in Spain - Houses for Rent in Busot",
                    "type": "organic",
                    "url": "https://www.airbnb.co.uk/rooms/9168035"
                },
                "44": {
                    "description": "Discover the most stylish places in Seville, including the intimate Corral del Rey and traditional tapas at El Rinconillo. Plus, shop vacation looks.",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "The Vacation Report: Seville Spain Travel Focus ...",
                    "type": "organic",
                    "url": "http://www.matchesfashion.com/us/womens/the-style-report/2015/11/the-cocktail-hour-issue/the-vacation-report-travel-focus-seville-city-break"
                },
                "45": {
                    "description": "Jump to Equestrian Vacations in Spain. - If you love to horseback ride through beautiful scenery, canter along deserted, golden sandy beaches and ...",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Horseback Riding Spain - Andalusian Horses - Horseback ...",
                    "type": "organic",
                    "url": "http://www.losalamosriding.co.uk/"
                },
                "46": {
                    "description": "Everyone has their image of Spain whether it be the Costas of package holiday fame, Majorca holidays, the beauty of the northern Basque region or the wonders ...",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Cooking Holidays or Cooking Vacations in Spain (Spanish ...",
                    "type": "organic",
                    "url": "http://www.cookingholidays.co.uk/pages/spain-menu.shtml"
                },
                "47": {
                    "description": "Country villa at torrox, Malaga with three bedrooms and private pool near to beach. Spain Vacation Rentals, spain villas.",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Spain Villas",
                    "type": "organic",
                    "url": "http://www.lamexicana.co.uk/"
                },
                "48": {
                    "description": "Cycling holidays on the northern coast of Spain and through the Picos de Europa mountains. Small family-run hotels. Luggage transport available.",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Guided and self guided cycling tours in Spain - Ibero Cycle",
                    "type": "organic",
                    "url": "http://www.iberocycle.com/"
                },
                "49": {
                    "description": "Sailing vacation in Spain Spain is a wonderful country with many different attractions; historical sites, beautiful nature, culture, beaches, sports, cuisine etc.",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Sailing vacation in Spain - Spain Yacht Charter",
                    "type": "organic",
                    "url": "http://www.spain-yachtcharter.com/cruising.asp"
                },
                "50": {
                    "description": "Buy Starting a Business in Spain (Starting a Business - Vacation Work Pub) (Starting a Business from Home: Choosing a Business, Getting Online, Reaching ...",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.amazon.co.uk › ... › Speciality Travel › Living & Working Abroad"
                        }
                    ],
                    "title": "Starting a Business in Spain (Starting a Business - Vacation ...",
                    "type": "organic",
                    "url": "http://www.amazon.co.uk/Starting-Business-Spain-Vacation-Choosing/dp/1854583077"
                },
                "51": {
                    "description": "Employment in Spain is highly regulated, with the main purpose to protect an employee's rights. ... Vacation of 21 business days for each full year worked.",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Employment law in Spain | Holidays | Contracts | Hiring ...",
                    "type": "organic",
                    "url": "http://www.spanish-living.com/jobs-employment-spain/employment-law"
                },
                "52": {
                    "description": "This lovely 6 bedroom beach house is a newly built home on the west coast of Ibiza. ... This modern 6 bedroom villa is situated in the hills above Calla Bassa in private gated gardens with spectacular views over the trees to the sea. ... This is a recently built luxury contemporary 6 ...",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Luxury Villas in Spain, Luxury Vacation Rentals in Spain ...",
                    "type": "organic",
                    "url": "http://www.royalvillaseurope.com/spain-rentals"
                },
                "53": {
                    "description": "All inclusive holidays to Spain with Thomas Cook. Find your perfect All inclusive holidays to Spain for your dream holiday.",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "All Inclusive Holidays to Spain 2016/2017 | Thomas Cook",
                    "type": "organic",
                    "url": "https://www.thomascook.com/holidays/spain/all-inclusive/"
                },
                "54": {
                    "description": "Enjoy a charming villa in Catalonia (north east Spain), including destinations such as ... a selection of the most unique vacation homes in the north east of Spain.",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Luxury Holiday Villas in Catalonia, Costa Brava & Barcelona",
                    "type": "organic",
                    "url": "http://www.charmingvillas.net/"
                },
                "55": {
                    "description": "Alhaurin De La Torre Villa, Alhaurin de la Torre: Holiday villa for rent from £600 per week. Read 19 reviews, view 24 photos, book online with traveller protection ...",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.homeaway.co.uk › ... › Alhaurin de la Torre"
                        },
                        {
                            "guessed_type": "review",
                            "type": "rating",
                            "votes": 19,
                            "score": 5,
                            "raw": " Rating: 5 - ‎19 reviews"
                        }
                    ],
                    "title": "luxury villa spain-vacation rentals-private pool-wifi-golf-ac ...",
                    "type": "organic",
                    "url": "https://www.homeaway.co.uk/p1004794"
                },
                "56": {
                    "description": "Search from over 9+ luxury Spain villas and vacation rentals from $4375 per week. Book your Spain villa online or call us on 1-866-341-8086 today.",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.thetopvillas.com › Europe"
                        }
                    ],
                    "title": "Spain Villas, Spain Vacation Rentals | Top Villas",
                    "type": "organic",
                    "url": "http://www.thetopvillas.com/spain/"
                },
                "57": {
                    "description": "Walking holidays in Spain from Walks in Spain, offering individual and group walking holidays in Spain, winter breaks, Camino de Santiago, Fallas, Valencia ...",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Walks in Spain: Walking Holidays in Spain",
                    "type": "organic",
                    "url": "http://www.walksinspain.com/"
                },
                "58": {
                    "description": "24 Nov 2009 - landscape, vacation home, costa del sol, andalusia,pool, Med sea ... Recently I wrote about how to find a winter rental in Spain, so thought I ...",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "What's a Winter Rental in Spain Like? - Soul Travelers 3",
                    "type": "organic",
                    "url": "http://www.soultravelers3.com/2009/11/whats-a-spain-winter-rental-like-extended-travel-digital-nomad-4hww-vacation-.html"
                },
                "59": {
                    "description": "Play golf courses in Spain and stay at award-winning golf hotels and resorts for great value prices. Read reviews from fellow golfers.",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Golf in Spain, Golf Holidays in Spain, Golf Breaks Spain",
                    "type": "organic",
                    "url": "http://www.golfbreaks.com/spain"
                },
                "60": {
                    "description": "Hello forum, We are a Canadian family looking to invest in an inexpensive property for vacations in Spain. Many Canadians still invest in ...",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Where to buy a vacation property in Spain? - Expat Forum",
                    "type": "organic",
                    "url": "http://www.expatforum.com/expats/spain-expat-forum-expats-living-spain/138078-where-buy-vacation-property-spain.html"
                },
                "61": {
                    "description": "Spain's best beach resorts at the Costa Brava in Catalonia, tourist information. ... Learn why it's a good idea to vacation in Spain this year. Continue reading →.",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Costa Brava Tourist Guide",
                    "type": "organic",
                    "url": "http://costabravatouristguide.com/"
                },
                "62": {
                    "description": "Spain was one of the first holiday destinations overseas that we flocked to in our masses, and the enduring popularity of cheap holidays to Spain shows no sign of stopping in 2016. So if you're looking for a discount holiday package we suggest you book early as popular resorts are ...",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Cheap Holidays to Spain | Compare Holidays | dealchecker ...",
                    "type": "organic",
                    "url": "http://www.dealchecker.co.uk/cheap-holidays/spain.html"
                },
                "63": {
                    "description": "Sunny Spain is an easy to reach destination with a great variety of horse riding holidays including point-to-point treks and beach riding.",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Finca Alcadeisa, horseback vacation Spain Unicorn Trails",
                    "type": "organic",
                    "url": "https://www.unicorntrails.com/europe/spain/fincaalcadeisa/"
                },
                "64": {
                    "description": "Discover great holiday deals to Spain with lastminute.com. With a fantastic range of holidays throughout Spain to choose from you'll be spoilt for choice.",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Spain Holidays | Cheap Spain Deals | lastminute.com",
                    "type": "organic",
                    "url": "http://www.lastminute.com/holidays/spain.html"
                },
                "65": {
                    "description": "Superb horse riding vacations in Spain for proficient riders. Join us for fantastic beach gallops and superb forest riding.",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Horse riding vacations in Spain with superb beach and ...",
                    "type": "organic",
                    "url": "http://www.fantasiaadventureholidays.com/horse_news.html"
                },
                "66": {
                    "description": "Holiday Rentals available directly from their owners in Spain, Europe choose from a huge selection of accommodations, including villas, apartments, condos ...",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Holiday Rentals by Owners in Spain, Europe Vacation Rental",
                    "type": "organic",
                    "url": "http://www.ownersrentals.com/search/Europe/Spain.html"
                },
                "67": {
                    "description": "We are one of the largest and most respected independent promoters of Holiday Ownership interests in Europe. Specialized in the commercial aspects and ...",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Diversified Vacation Ownership - Costa del Sol, Spain",
                    "type": "organic",
                    "url": "http://www.diversifiedresorts.com/vacation-ownership.php"
                },
                "68": {
                    "description": "Love Home Swap helps you find the ideal home exchange in Spain. Join the world's biggest home swap club and save up to 90% on travel costs.",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Home Exchange | Spain | Love Home Swap",
                    "type": "organic",
                    "url": "http://www.lovehomeswap.com/location/spain"
                },
                "69": {
                    "description": "You want to spend your next summer vacation in Spain in a rental holiday home, house, villa or apartment on the Costa Brava? For vacation rentals of holiday ...",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Search vacation property for holiday rentals in Spain, Costa ...",
                    "type": "organic",
                    "url": "http://www.immocostabrava.com/en/search-vacation-property-for-holiday-rentals-in-spain-costa-brava-villas-houses-apartments-flats-for-rent"
                },
                "70": {
                    "description": "Explore Spain's countryside with the best cycling routes in our self led and guided bike tours. ... This turned into the best vacation we've ever had, at any price.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Bicycle Touring Spain: The Best Spain Bike Tours",
                    "type": "organic",
                    "url": "http://www.cyclingcountry.com/CycleTours/Spain.htm"
                },
                "71": {
                    "description": "17 Jan 2014 - Some of you may wonder what Alexander Megos has been up to lately. So did I... well I knew he was on vacation in Spain, but no more than ...",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "UKC News - Alex Megos talks about his Spanish vacation",
                    "type": "organic",
                    "url": "http://www.ukclimbing.com/news/item.php?id=68654"
                },
                "72": {
                    "description": "The perfect villa for rental located in Ronda, Malaga, Andalucia, Spain. The White Olive is ... Vacation Rentals Spain | Farmhouse Ronda | Holiday Rentals Spain.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Villa for rental Ronda Malaga Spain | The White Olive ...",
                    "type": "organic",
                    "url": "http://www.thewhiteolive.com/"
                },
                "73": {
                    "description": "Self catering acommodation. Five bedroom holiday home, two bedroom and one bedroom cottage rental in the white villages of rural andalucia.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Self-catering vacation rentals in rural Andalucia Spain - Self ...",
                    "type": "organic",
                    "url": "http://www.vivasiesta.com/"
                },
                "74": {
                    "description": "Whether you're visiting for business or on vacation, you'll be impressed with our well-designed golfing packages. With a wide range of courses of every variety, ...",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Barcelona Golf: Golf in Spain | Golf Holidays in Spain",
                    "type": "organic",
                    "url": "http://www.barcelonagolf.com/"
                },
                "75": {
                    "description": "The best spa hotels, wellness breaks, health retreats & weight loss holidays. View our spa & hotel offers in Spain and Portugal.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Spa hotels Spain, wellness packages & weight loss holidays",
                    "type": "organic",
                    "url": "http://www.spa-in-spain.com/"
                },
                "76": {
                    "description": "Search the best beach holidays in Spain. Secure today with a low deposit. ATOL protected. Book now.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Cheap holidays to Spain | On the Beach",
                    "type": "organic",
                    "url": "https://www.onthebeach.co.uk/destinations/spain"
                },
                "77": {
                    "description": "7 May 2015 - FORGET Majorca and Tenerife, Greek holiday islands are the best in Europe, according to rankings based on a staggering 140 million ...",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.express.co.uk › Travel › Travel News"
                        }
                    ],
                    "title": "Forget Spain and Italy: Beautiful holiday islands of GREECE ...",
                    "type": "organic",
                    "url": "http://www.express.co.uk/travel/articles/575302/Forget-Spain-and-Italy-The-beautiful-holiday-islands-of-GREECE-are-best-in-Europe"
                },
                "78": {
                    "description": "GB Vacation rental · FR Location de vacances ... Find your ideal holiday rental in France, Corsica, Italy, Spain & Croatia. Duration of your stay, 7 nights. 7 nights.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Holiday rentals in France, Corsica, Italy, Spain and Croatia ...",
                    "type": "organic",
                    "url": "http://www.odalys-vacation-rental.com/"
                },
                "79": {
                    "description": "Welcome Cottages - A part of the Wyndham Vacation Rentals® Family of Brands. Through Wyndham Vacation Rentals, we offer holidaymakers like you the ...",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Wyndham Vacation Rentals | Holiday cottages in the UK ...",
                    "type": "organic",
                    "url": "https://www.welcomecottages.com/info/wyndham-vacation-rentals"
                },
                "80": {
                    "description": "Art Vacations in Spain. Painting Holidays in Extremadura - SW Spain and Wales Beginners and experienced welcome. 7 nights : Stay in a Conquistador Palace, ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Holiday Artists - Art Vacations - Painting Holidays and Art ...",
                    "type": "organic",
                    "url": "http://www.holidayartists.com/painting.html"
                },
                "81": {
                    "description": "View photos from holiday makers on vacation in Spain. Spanish beaches, mountains, cities, resorts, ancient ruins, sights and more. All images captured by ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.360travelguide.com › Travel Guides › Europe › Spain"
                        }
                    ],
                    "title": "Spain Vacation Photos | Spanish Holiday Images & Travel ...",
                    "type": "organic",
                    "url": "http://www.360travelguide.com/Spain/images.asp"
                },
                "82": {
                    "description": "Albatros Villa, Your Next Holiday Home Rentals Villa In Spain, With Free Heated Pool, Pool Heating, Free wireless WiFi Internet, AirCon, Pool Table, Table ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Holidays | Holiday House | Vacation Rentals | Home | Spain ...",
                    "type": "organic",
                    "url": "http://www.albatrosvilla.com/"
                },
                "83": {
                    "description": "Wide choice of dancing holidays & vacations including salsa, flamenco, ... Learn Tango & Spanish in beautiful Granada, Spain, from €325 (5 days) ex flights.",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [
                        {
                            "guessed_type": "review",
                            "type": "rating",
                            "votes": 6,
                            "score": 5,
                            "raw": " Rating: 5 - ‎6 reviews"
                        }
                    ],
                    "title": "Dancing holidays. Dancing vacations & holidays. World's ...",
                    "type": "organic",
                    "url": "http://www.responsibletravel.com/holidays/dancing"
                },
                "84": {
                    "description": "55 results - Stunning Luxury Villas in Spain from Abercrombie & Kent. ... predictability of the summer weather ensures your villa vacation lives long in the memory.",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Luxury Villas In Spain, Luxury Spanish Villas - A&K Villas",
                    "type": "organic",
                    "url": "http://www.akvillas.com/luxury-villas-spain/"
                },
                "85": {
                    "description": "Everything you need to know about galicia in spain's green northern region ... are often promoted as the areas main vacation attractions, beautiful beaches fill ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "GALICIA SPAIN | Galicia Guide",
                    "type": "organic",
                    "url": "http://www.galiciaguide.com/Galicia-index.html"
                },
                "86": {
                    "description": "12 Jan 2016 - Pack your vacation capsule wardrobe for Spain with the complete guide from What to Wear On Vacation. Don't know what to take? Fed up with ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "What to Wear in Spain: Packing checklists and clothing tips ...",
                    "type": "organic",
                    "url": "http://www.whattowearonholiday.com/us/destinations/europe/spain/66-what-to-wear-in-spain.php"
                },
                "87": {
                    "description": "3 Bedroom, 2 bath Self Catering Holiday Rental Apartment in La Cala de Mijas, Spain. Rent our holiday house today!",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Spanish Vacation Rental - 3 Bedroom Holiday Rental ...",
                    "type": "organic",
                    "url": "http://www.spanishvacationrental.com/"
                },
                "88": {
                    "description": "The premier online guide for useful information about Andalucia and Southern Spain since 1996.",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Premier online guide for useful information about Andalucia ...",
                    "type": "organic",
                    "url": "http://www.andalucia.com/"
                },
                "89": {
                    "description": "Oxygen Vacation Spain: Spain is a very popular destination for holiday makers in need of medical oxygen. The wide variaty of equipment and a thorough ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Oxygen Vacation Spain - Oxygenworldwide",
                    "type": "organic",
                    "url": "http://oxygenworldwide.com/en/help/wiki/121-oxygen-vacation-spain.html"
                },
                "90": {
                    "description": "Large selection of affordable holiday rentals Spain vacation rentals Spain and worldwide. Owners advertise for free!",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "holiday rental Spain vacation rental Spain",
                    "type": "organic",
                    "url": "http://www.holiday-rentals-worldwide.co.uk/auswobj_e.aspx?Country=ES"
                },
                "91": {
                    "description": "Holiday Villas rentals in Mijas, Costa del Sol, Information on Golfing in Mijas, Spain.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Villas in Mijas Property, Holiday, Vacation Rentals, Costa ...",
                    "type": "organic",
                    "url": "http://www.villasinmijasspain.com/"
                },
                "92": {
                    "description": "Planning on visiting Spain with your baby? Check out our complete guide to family holidays in Spain, including information on food, travel and healthcare.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Family holidays in Spain - BabyCentre",
                    "type": "organic",
                    "url": "http://www.babycentre.co.uk/a554507/family-holidays-in-spain"
                },
                "93": {
                    "description": "The Spain of a million wish-you-were-here postcards, the Balearic Islands have all the sun and sea attributes to write home about. But there is...",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.lonelyplanet.com › Europe › Mediterranean Europe › Spain"
                        }
                    ],
                    "title": "Mallorca, Menorca & Ibiza, Spain - Lonely Planet",
                    "type": "organic",
                    "url": "http://www.lonelyplanet.com/spain/balearic-islands"
                },
                "94": {
                    "description": "Horseback riding vacations in Spain! Enquire about our ONE OFF exploring trek “Riding Home from Ronda” April 21st -25th 2016. Ride Andalucia is a specialist ...",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Ride Andalucia - Horseback riding holidays in southern Spain",
                    "type": "organic",
                    "url": "http://rideandalucia.com/"
                },
                "95": {
                    "description": "Castle vacation tips, plans and strategies for history enthusiasts visiting Europe. ... Germany, Spain or Austria, and discover some magnificent castles en route.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Castle Vacations: Unforgettable Vacation Trips To Castles in ...",
                    "type": "organic",
                    "url": "http://www.exploring-castles.com/castle_vacations.html"
                },
                "96": {
                    "description": "If you're looking for a Vacation Rentals in Puerto Pollensa (Mallorca), then the team at Balearic Villas have all the local knowledge, and fantastic properties, you ...",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Vacation Rentals in Puerto Pollensa, Spain | by Balearic ...",
                    "type": "organic",
                    "url": "https://www.balearic-villas.com/vacation-rentals-in-puerto-pollensa-spain-19-54.html"
                },
                "97": {
                    "description": "Explore Spain with Rough Guides: find out the best places to visit, when to go, view itineraries and read about Barcelona, flamenco, tapas and Semana Santa.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Places to Visit in Spain | Spain Travel Guide | Rough Guides",
                    "type": "organic",
                    "url": "http://www.roughguides.com/destinations/europe/spain/"
                },
                "98": {
                    "description": "A guide to vacations, travel, and hotels in Madrid, Madrid, Spain.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Destination Traveler: Spain - vacation, travel, hotels in ...",
                    "type": "organic",
                    "url": "http://www.destination-traveler.com/spain/regions/madrid/madrid.asp"
                },
                "99": {
                    "description": "Agency representing several schools in Spain and Latin America.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Study Spanish language courses in Spain, Cuba, Latin ...",
                    "type": "organic",
                    "url": "http://www.spanishstudyholidays.com/"
                }
            },
            "paid": {
                "1": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "2": {
                    "description": "Private customized tours with driver guides",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Barcelona shore trips - bestprivatetours.com‎",
                    "type": "ad",
                    "url": "http://www.bestprivatetours.com/"
                },
                "3": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday - Zwerfdierenindahab.nl‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "4": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "5": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "6": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "7": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "8": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "9": {
                    "description": "Ilusiones como tratamiento de vida para niños con enfermedades graves",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "10": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "11": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "12": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "13": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "14": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "15": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "16": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "17": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "18": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "19": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "20": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "21": {
                    "description": "Villa rentals in Costa Brava, Costa Dorada & Barcelona. Book now!",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Holiday villas in Spain - catalanholidays.com‎",
                    "type": "ad",
                    "url": "http://www.catalanholidays.com/listar.php?TipoGestion=A&TipoInmueble=-1&lang=en&country=ESP"
                },
                "22": {
                    "description": "Rental Marketplace. Owners Direct!",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Spain Holiday Rental - Long & Short Term - Furn & Unfurn‎",
                    "type": "ad",
                    "url": "https://www.sublet.com/State_Rentals/Spain_Rentals.asp?source=10140"
                },
                "23": {
                    "description": "Explore the wonders of Rwanda Culture, Community & Wild Life",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "A Holiday of a Life Time‎",
                    "type": "ad",
                    "url": "http://azizilife.com/get-involved/experiences"
                },
                "24": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "25": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "26": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "27": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                },
                "28": {
                    "description": "Charming tours of Andalucia for the more discerning traveller",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Tours of Andalucia - lemonvalleyholidays.com‎",
                    "type": "ad",
                    "url": "http://www.lemonvalleyholidays.com/Home-tours-of-andalucia-and-spain.php"
                },
                "29": {
                    "description": "\"Una ilusión es algo que se quiere de todo corazón\"- Cristina,12 años",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Make-A-Wish Spain‎",
                    "type": "ad",
                    "url": "http://www.makeawishspain.org/es"
                },
                "30": {
                    "description": "Cheap and beautiful House rental in Egypt. Book and Help a Stray!",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Help a stray with Holiday‎",
                    "type": "ad",
                    "url": "http://zwerfdierenindahab.nl/en/help-a-stray-with-your-holiday/"
                }
            },
            "place": {},
            "shopping": {},
            "universal": {
                "1": {
                    "description": "Offers vacation rentals and accommodations in touristic regions. Apartments, villas and townhouses booked directly with the property owners.",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [
                        {
                            "links": [
                                {
                                    "title": "Costa del Sol",
                                    "description": "",
                                    "url": "http://www.spain-holiday.com/Costa-del-Sol/holiday-rentals"
                                },
                                {
                                    "title": "Spain",
                                    "description": "",
                                    "url": "http://www.spain-holiday.com/Spain/holiday-rentals"
                                },
                                {
                                    "title": "Costa Blanca",
                                    "description": "",
                                    "url": "http://www.spain-holiday.com/Costa-Blanca/holiday-rentals"
                                },
                                {
                                    "title": "Beach villas for rent in Spain ...",
                                    "description": "",
                                    "url": "http://www.spain-holiday.com/Spain/holiday-rentals/beach"
                                }
                            ],
                            "type": "site_links"
                        }
                    ],
                    "title": "Spain Holiday - Holiday villas, apartments and cottages for ...",
                    "type": "organic",
                    "url": "http://www.spain-holiday.com/"
                },
                "2": {
                    "description": "Vacation Villas - your answer to finding the perfect holiday home to rent or to buy on the Costa Blanca in Spain. We have the finest selection of properties to rent ...",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Costa Blanca, Spain Villa Rentals - rent in Javea and Denia",
                    "type": "organic",
                    "url": "http://www.vacationvillasspain.com/"
                },
                "3": {
                    "description": "Spain Holidays: Find Spain holiday packages and city breaks to Spain on TripAdvisor by comparing prices and reading Spain hotel ... 1. Barcelona Vacations.",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "The Best Spain Holidays 2016 - TripAdvisor",
                    "type": "organic",
                    "url": "https://www.tripadvisor.co.uk/Vacation_Packages-g187427-Spain-Vacations.html"
                },
                "4": {
                    "description": "Spain Tourism: TripAdvisor has 9717503 reviews of Spain Hotels, Attractions, and Restaurants making it your best Spain resource.",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Spain Tourism: Best of Spain - TripAdvisor",
                    "type": "organic",
                    "url": "https://www.tripadvisor.co.uk/Tourism-g187427-Spain-Vacations.html"
                },
                "5": {
                    "description": "5 Jan 2016 - Our experts' pick of the top 10 beach and seaside holidays in Spain for 2016, including the best beaches for watersports, families and ...",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "The top 10 beach holidays in Spain - Telegraph",
                    "type": "organic",
                    "url": "http://www.telegraph.co.uk/travel/destinations/europe/spain/articles/The-top-10-beach-holidays-in-Spain/"
                },
                "6": {
                    "description": "9 Jul 2014 - From a cottage in the mountains to stylish pads in Seville and Barcelona, we select the best self-catering properties in Spain to keep the kids ...",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.theguardian.com › Travel › Spain holidays"
                        }
                    ],
                    "title": "10 of the best family self-catering holidays in Spain | Travel ...",
                    "type": "organic",
                    "url": "http://www.theguardian.com/travel/2014/jul/09/10-best-self-catering-holidays-spain"
                },
                "7": {
                    "description": "Villa, finca, townhouse, apartment or new-build properties for sale in and around Javea and Denia, Costa Blanca, Spain. Investment properties too.",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Vacation Villas Properties for sale in Javea and Denia, Spain",
                    "type": "organic",
                    "url": "http://www.vacationvillassales.com/"
                },
                "8": {
                    "description": "Holiday in the sun: 2.100 holiday houses and holiday flats in Spain, on Majorca or the Canary Islands, in Andalusia, Catalonia or on the Costa Blanca. ¡Vamos!",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.vacation-apartments.com › Europe"
                        },
                        {
                            "guessed_type": "review",
                            "type": "rating",
                            "votes": 1600,
                            "score": 4.9,
                            "raw": " Rating: 4.9 - ‎1,600 votes"
                        }
                    ],
                    "title": "holiday houses and holiday flats Spain - Vacation in Spain",
                    "type": "organic",
                    "url": "http://www.vacation-apartments.com/europe/spain/"
                },
                "9": {
                    "description": "10+ items - Vacation Rentals in Spain. Here you find 4395 vacation rentals, ...",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Vacation Rentals Spain Vacation Rental Spain Rent Holiday ...",
                    "type": "organic",
                    "url": "http://www.rent-holiday-homes.com/Vacation-Rentals-Spain-c192_p1.html"
                },
                "10": {
                    "description": "Paradores Spain Special Offers - Great Selection of discounted 7 night Parador tours with routes all over Spain. Book early for best offers.",
                    "markup": 0,
                    "page_number": 1,
                    "rich_snippets": [],
                    "title": "Paradores Special Offers - Spain Vacation Tours Packages ...",
                    "type": "organic",
                    "url": "http://www.totallyspain.com/spain_travel_offers.asp"
                },
                "11": {
                    "description": "This is also a top location for winter vacations with tourists trying to escape the colder months, as the south of Spain, in particular the coast of Andalusia, is often ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.casamundo.co.uk › Holiday lettings"
                        },
                        {
                            "guessed_type": "review",
                            "type": "rating",
                            "votes": 14340,
                            "score": 4.1,
                            "raw": " Rating: 4.1 - ‎14,340 votes"
                        }
                    ],
                    "title": "Book holiday homes in Spain online with CASAMUNDO",
                    "type": "organic",
                    "url": "http://www.casamundo.co.uk/holiday-rentals/spain"
                },
                "12": {
                    "description": "Find the best surfing locations in Spain at Errant Surf. ... We provide some of the best surfing holidays and surf vacations in Spain and have done so since 2005.",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Spain - Errant Surf",
                    "type": "organic",
                    "url": "https://www.errantsurf.com/locations/World-Europe-Spain"
                },
                "13": {
                    "description": "Marriott's Marbella Beach Resort Marriott Vacation Club Exchange Resort. Urb. Marbella del Este, Crta. de Cádiz, Km 193, 29604 Marbella, Costa del Sol, Spain",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Marriott's Marbella Beach Resort - Marriott Vacation Club ...",
                    "type": "organic",
                    "url": "http://www.marriottvacationclub.com/vacation-resorts/marriott-marbella-beach-club/overview.shtml"
                },
                "14": {
                    "description": "They are ideal for a wonderful holiday or short vacation in Spain with the family. Many houses have space for 2 or 3 families. There are also spacious villa ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Spain Holiday rentals, villa rentals, Spain vacation self ...",
                    "type": "organic",
                    "url": "http://www.cottage-rental.com/spain-holiday-rentals.asp"
                },
                "15": {
                    "description": "Villa Rentals Spain & Villa Rentals Italy from El Sol Villa Specialists. We provide the best luxury vacation rentals in Spain, France, Italy & worldwide.",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "El Sol Villas: Luxury Villa Rentals | Vacation Home Rentals",
                    "type": "organic",
                    "url": "http://www.elsolvillas.com/"
                },
                "16": {
                    "description": "Find a Marriott Vacation Club hotel in Spain offering accommodation for business & leisure travellers. Hotels in Spain offering quality service & facilities at ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Marriott Vacation Club Hotels, Spain. Choose a hotel at ...",
                    "type": "organic",
                    "url": "http://www.marriott.co.uk/hotel-search/spain.hotels.marriott-vacation-club-international/"
                },
                "17": {
                    "description": "",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "http://vacationclub.silverpoint.com/english/silverpoint/spain.aspx",
                    "type": "image",
                    "url": "http://vacationclub.silverpoint.com/english/silverpoint/spain.aspx"
                },
                "18": {
                    "description": "",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "http://blog.visafirst.com/europe-by-road-the-5-best-european-driving-vacation-routes/",
                    "type": "image",
                    "url": "http://blog.visafirst.com/europe-by-road-the-5-best-european-driving-vacation-routes/"
                },
                "19": {
                    "description": "",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "https://www.expedia.co.uk/Barcelona.d179992.Holidays-City-Breaks",
                    "type": "image",
                    "url": "https://www.expedia.co.uk/Barcelona.d179992.Holidays-City-Breaks"
                },
                "20": {
                    "description": "",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "http://www.vacation-key.com/spain",
                    "type": "image",
                    "url": "http://www.vacation-key.com/spain"
                },
                "21": {
                    "description": "Totally Spain is a savvy and reputable Spain & Portugal Travel Agency dedicated to organising exceptional Custom Designed Private Travel, Tours & Vacations ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Totally Spain: Spain Travel - Travel Agent - Spain Tour",
                    "type": "organic",
                    "url": "http://www.totallyspain.com/"
                },
                "22": {
                    "description": "Find all inclusive holidays in Spain with easyJet holidays. With great all inclusive deals to top Spanish destinations such as Tenerife and Majorca, you can get ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [],
                    "title": "Spain All Inclusive Holidays | easyJet holidays",
                    "type": "organic",
                    "url": "http://www.easyjet.com/en/holidays/events/spain-all-inclusive/"
                },
                "23": {
                    "description": "13 Aug 2015 - Take a break from your old Costas favourite to spread your towel on our choice of the 10 absolute best beaches in Spain - a country with more ...",
                    "markup": 0,
                    "page_number": 2,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.mirror.co.uk › Lifestyle › Travel › Spain holidays"
                        }
                    ],
                    "title": "Top 10 guide to the best beaches in Spain - Mirror Online",
                    "type": "organic",
                    "url": "http://www.mirror.co.uk/lifestyle/travel/top-ten-spain-best-beaches-402325"
                },
                "24": {
                    "description": "The Ebro Delta, or Delta de L'Ebre, is one of the best bird watching sites in Europe - easily on a par with the Coto Doñana and the Camargue - and without doubt ...",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "birding holidays vacations in Spain EBRO DELTA euro trip ...",
                    "type": "organic",
                    "url": "http://www.catalanbirdtours.com/Spain birding/EBRO birdwatching tours.html"
                },
                "25": {
                    "description": "Independent Bike Vacation in Spain – Route of the Caliphate ... This biking vacation in Andalucia is available as a self guided cycle tour which we have graded ...",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Route Caliphate Bike Vacation Tour in Spain",
                    "type": "organic",
                    "url": "http://www.hookedoncycling.co.uk/spain-route-of-the-caliphate/"
                },
                "26": {
                    "description": "Spain Villa Vacation Rentals,Holiday Home, Bed & Breakfast BNB B&B Luxury Properties, Apartment Rental in Andalusia, Costa del Sol, direct by owner or ...",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Spain Villa Vacation Rentals Spain Holiday Home Bed ...",
                    "type": "organic",
                    "url": "http://www.vacation-key.com/spain"
                },
                "27": {
                    "description": "Welcome To Miraflores Vacation Properties ... Miraflores, an award-winning luxury resort of quality residential properties and vacation homes in Southern Spain.",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Miraflores: Award-Winning Luxury Development Resort ...",
                    "type": "organic",
                    "url": "http://www.miraflores.com/"
                },
                "28": {
                    "description": "Andalucia Rentals specialising in long rentals in the provinces of Andalucia, Southern Spain.",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Andalucia Rentals - long term rentals - and holiday lets in ...",
                    "type": "organic",
                    "url": "http://www.andaluciarentals.com/"
                },
                "29": {
                    "description": "Unique villas in Spain with private pools, all handpicked by own experts! Book your family holiday in Spain directly from the owners!",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Villas in Spain | Holiday Rentals in Spain | Oliver's Travels",
                    "type": "organic",
                    "url": "http://www.oliverstravels.com/spain/"
                },
                "30": {
                    "description": "Find your perfect property in Spain, search a wide range of properties for sale in Spain with Rightmove.",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Property for sale in Spain - Spanish Property for Sale",
                    "type": "organic",
                    "url": "http://www.rightmove.co.uk/overseas-property/in-Spain.html"
                },
                "31": {
                    "description": "Just a 2 and a half hour flight and you can be enjoying golf in the sunshine!",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "All Inclusive golf holidays in Spain - Premier Iberian Golf ...",
                    "type": "organic",
                    "url": "http://www.premieriberian.com/golf_holiday_filtered.aspx?area=41&name=Spain&filter=16"
                },
                "32": {
                    "description": "Spain or Thailand, Which Vacation Destination is Cheaper – You Might Be Surprised. May 28, 2011. When I was a kid, Spain was the preferred holiday ...",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Spain or Thailand, Which Vacation Destination is Cheaper ...",
                    "type": "organic",
                    "url": "http://seriouslyspain.com/spain-or-thailand-which-vacation-destination-is-cheaper-you-might-be-surprised"
                },
                "33": {
                    "description": "Planning to spend cheap holiday in Spain 2016? Here are a lot of tours and discount vacation packages to Spain. Check prices and choose your trip with ...",
                    "markup": 0,
                    "page_number": 3,
                    "rich_snippets": [],
                    "title": "Holidays in Spain 2016: discount prices, vacation packages ...",
                    "type": "organic",
                    "url": "http://tripvariator.co.uk/spain/"
                },
                "34": {
                    "description": "Whether you are looking for guided or self-guided wine tours to Spain´s wine regions, short gastronomic getaways, a roadtrip or long vacations with cultural ...",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Wine Tours in Spain by winetourismspain.com",
                    "type": "organic",
                    "url": "http://winetourismspain.com/"
                },
                "35": {
                    "description": "9140 Spain vacation homes. Good availability and great rates for vacation homes in Spain. Read reviews and choose the best vacation home for your vacation.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Booking.com : Spain vacation homes. 9140 vacation homes ...",
                    "type": "organic",
                    "url": "http://www.booking.com/holiday-homes/country/es.html"
                },
                "36": {
                    "description": "Horse riding is deeply ingrained into Spanish culture and there are many equestrian vacations in Spain to choose from. With a combination of quality horses, ...",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Riding Holidays in Spain - In The Saddle",
                    "type": "organic",
                    "url": "https://www.inthesaddle.com/rides/search/spain"
                },
                "37": {
                    "description": "Spain offers spectacular countryside, much of which is totally unspoilt. ... Riding holidays and vacations overview. Riding ... Horse Riding Holidays, Spain.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.farandride.com › Riding Holidays"
                        }
                    ],
                    "title": "Horse riding holidays in Spain (11 destinations) - Far and Ride",
                    "type": "organic",
                    "url": "http://www.farandride.com/riding-holidays/spain/"
                },
                "38": {
                    "description": "Vacation Ownership Specials - Take advantage of timeshare offers at resort destinations worldwide – each ... Marriott's Marbella Beach ResortMarbella, Spain.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Marriott's Marbella Beach Resort - Marriott Vacation Club",
                    "type": "organic",
                    "url": "http://www.marriottvacationclub.eu/european-resorts/marbella/"
                },
                "39": {
                    "description": "Ronda is an excellent base for the independent traveller to explore Andalucia, a beautiful part of Southern Spain - your ideal summer vacation destination.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Holiday Villas Andalucia | Luxury Villas to Rent | Holidays ...",
                    "type": "organic",
                    "url": "http://www.real-ronda.com/"
                },
                "40": {
                    "description": "25 Jul 2015 - Comprehensive travel, vacation, lodging & tourism guide to Spain.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Spanish Holiday - Vacation in Spain - Travel ...",
                    "type": "organic",
                    "url": "http://www.allspainaccommodation.com/"
                },
                "41": {
                    "description": "22 May 2015 - Superhero's day off! Arrow star Stephen Amell goes shirtless as he and his bikini-clad wife enjoy a vacation in Marbella, Spain on Thursday.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Arrow star Stephen Amell goes shirtless on vacation",
                    "type": "organic",
                    "url": "http://www.dailymail.co.uk/tvshowbiz/article-3093279/Arrow-star-Stephen-Amell-goes-shirtless-bikini-clad-wife-enjoy-vacation-Spain.html"
                },
                "42": {
                    "description": "Horse Riding Holidays. Riding Holidays Spain. Andalucia Short Stay · Andalucia One Week · Barcelona/Costa Brava · Madrid · Mallorca. Riding Holidays UK.",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [],
                    "title": "Spanish Riding Holiday | Equestrian Vacation Malaga ...",
                    "type": "organic",
                    "url": "http://www.equestrian-escapes.com/riding-holidays-Spain-luxury/"
                },
                "43": {
                    "description": "... and apartment accommodation in Barcelona for your holiday rental in Spain from ... Fully Renovated Building with Vacation Rentals Apartments - Sant Pau 1 ...",
                    "markup": 0,
                    "page_number": 4,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.ownersdirect.co.uk › ... › Spain › Catalonia › Barcelona Province"
                        },
                        {
                            "guessed_type": "review",
                            "type": "rating",
                            "votes": 152,
                            "score": 4.5,
                            "raw": " Rating: 4.5 - ‎152 reviews - ‎Starting from £64.20"
                        }
                    ],
                    "title": "Apartments in Barcelona - Self Catering Barcelona",
                    "type": "organic",
                    "url": "https://www.ownersdirect.co.uk/rentals/spain/barcelona/r991"
                },
                "44": {
                    "description": "Spain Holiday Rentals - Find wonderful and unique local holiday rentals in Spain ... Marvelous Golf Course View - Vacation Townhouse in La Torre Golf Resort.",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Spain Holiday Rentals: Spain Holiday Apartment, Home and ...",
                    "type": "organic",
                    "url": "http://www.alwaysonvacation.co.uk/holiday-rentals/spain/nnes"
                },
                "45": {
                    "description": "Spain is surely worth a vacation or even a business or short holiday trip, as the country is diverse in many ways, from language and people to climate, landscape ...",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Accommodation and travel guide for Spain holiday and events",
                    "type": "organic",
                    "url": "http://www.spaindreams.com/"
                },
                "46": {
                    "description": "24 Nov 2014 - These Thrasher vacation edits are kicking off! Watch below to see the Spanish edition of their venture and to witness some quality lurking from ...",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Thrasher Vacation: Spain - Sidewalk Skateboarding",
                    "type": "organic",
                    "url": "http://sidewalkmag.com/skateboard-news/thrasher-vacation-spain.html"
                },
                "47": {
                    "description": "Entire home/flat for £36. The house provides: 115m2 inside,180m2 outside,wifi,TV 3D,grill,",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.airbnb.co.uk › Spain › Comunidad Valenciana › Busot"
                        }
                    ],
                    "title": "Beautiful vacation home in Spain - Houses for Rent in Busot",
                    "type": "organic",
                    "url": "https://www.airbnb.co.uk/rooms/9168035"
                },
                "48": {
                    "description": "Discover the most stylish places in Seville, including the intimate Corral del Rey and traditional tapas at El Rinconillo. Plus, shop vacation looks.",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "The Vacation Report: Seville Spain Travel Focus ...",
                    "type": "organic",
                    "url": "http://www.matchesfashion.com/us/womens/the-style-report/2015/11/the-cocktail-hour-issue/the-vacation-report-travel-focus-seville-city-break"
                },
                "49": {
                    "description": "Jump to Equestrian Vacations in Spain. - If you love to horseback ride through beautiful scenery, canter along deserted, golden sandy beaches and ...",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Horseback Riding Spain - Andalusian Horses - Horseback ...",
                    "type": "organic",
                    "url": "http://www.losalamosriding.co.uk/"
                },
                "50": {
                    "description": "Everyone has their image of Spain whether it be the Costas of package holiday fame, Majorca holidays, the beauty of the northern Basque region or the wonders ...",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Cooking Holidays or Cooking Vacations in Spain (Spanish ...",
                    "type": "organic",
                    "url": "http://www.cookingholidays.co.uk/pages/spain-menu.shtml"
                },
                "51": {
                    "description": "Country villa at torrox, Malaga with three bedrooms and private pool near to beach. Spain Vacation Rentals, spain villas.",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Spain Villas",
                    "type": "organic",
                    "url": "http://www.lamexicana.co.uk/"
                },
                "52": {
                    "description": "Cycling holidays on the northern coast of Spain and through the Picos de Europa mountains. Small family-run hotels. Luggage transport available.",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Guided and self guided cycling tours in Spain - Ibero Cycle",
                    "type": "organic",
                    "url": "http://www.iberocycle.com/"
                },
                "53": {
                    "description": "Sailing vacation in Spain Spain is a wonderful country with many different attractions; historical sites, beautiful nature, culture, beaches, sports, cuisine etc.",
                    "markup": 0,
                    "page_number": 5,
                    "rich_snippets": [],
                    "title": "Sailing vacation in Spain - Spain Yacht Charter",
                    "type": "organic",
                    "url": "http://www.spain-yachtcharter.com/cruising.asp"
                },
                "54": {
                    "description": "Buy Starting a Business in Spain (Starting a Business - Vacation Work Pub) (Starting a Business from Home: Choosing a Business, Getting Online, Reaching ...",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.amazon.co.uk › ... › Speciality Travel › Living & Working Abroad"
                        }
                    ],
                    "title": "Starting a Business in Spain (Starting a Business - Vacation ...",
                    "type": "organic",
                    "url": "http://www.amazon.co.uk/Starting-Business-Spain-Vacation-Choosing/dp/1854583077"
                },
                "55": {
                    "description": "Employment in Spain is highly regulated, with the main purpose to protect an employee's rights. ... Vacation of 21 business days for each full year worked.",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Employment law in Spain | Holidays | Contracts | Hiring ...",
                    "type": "organic",
                    "url": "http://www.spanish-living.com/jobs-employment-spain/employment-law"
                },
                "56": {
                    "description": "This lovely 6 bedroom beach house is a newly built home on the west coast of Ibiza. ... This modern 6 bedroom villa is situated in the hills above Calla Bassa in private gated gardens with spectacular views over the trees to the sea. ... This is a recently built luxury contemporary 6 ...",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Luxury Villas in Spain, Luxury Vacation Rentals in Spain ...",
                    "type": "organic",
                    "url": "http://www.royalvillaseurope.com/spain-rentals"
                },
                "57": {
                    "description": "All inclusive holidays to Spain with Thomas Cook. Find your perfect All inclusive holidays to Spain for your dream holiday.",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "All Inclusive Holidays to Spain 2016/2017 | Thomas Cook",
                    "type": "organic",
                    "url": "https://www.thomascook.com/holidays/spain/all-inclusive/"
                },
                "58": {
                    "description": "Enjoy a charming villa in Catalonia (north east Spain), including destinations such as ... a selection of the most unique vacation homes in the north east of Spain.",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Luxury Holiday Villas in Catalonia, Costa Brava & Barcelona",
                    "type": "organic",
                    "url": "http://www.charmingvillas.net/"
                },
                "59": {
                    "description": "Alhaurin De La Torre Villa, Alhaurin de la Torre: Holiday villa for rent from £600 per week. Read 19 reviews, view 24 photos, book online with traveller protection ...",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.homeaway.co.uk › ... › Alhaurin de la Torre"
                        },
                        {
                            "guessed_type": "review",
                            "type": "rating",
                            "votes": 19,
                            "score": 5,
                            "raw": " Rating: 5 - ‎19 reviews"
                        }
                    ],
                    "title": "luxury villa spain-vacation rentals-private pool-wifi-golf-ac ...",
                    "type": "organic",
                    "url": "https://www.homeaway.co.uk/p1004794"
                },
                "60": {
                    "description": "Search from over 9+ luxury Spain villas and vacation rentals from $4375 per week. Book your Spain villa online or call us on 1-866-341-8086 today.",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.thetopvillas.com › Europe"
                        }
                    ],
                    "title": "Spain Villas, Spain Vacation Rentals | Top Villas",
                    "type": "organic",
                    "url": "http://www.thetopvillas.com/spain/"
                },
                "61": {
                    "description": "Walking holidays in Spain from Walks in Spain, offering individual and group walking holidays in Spain, winter breaks, Camino de Santiago, Fallas, Valencia ...",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Walks in Spain: Walking Holidays in Spain",
                    "type": "organic",
                    "url": "http://www.walksinspain.com/"
                },
                "62": {
                    "description": "24 Nov 2009 - landscape, vacation home, costa del sol, andalusia,pool, Med sea ... Recently I wrote about how to find a winter rental in Spain, so thought I ...",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "What's a Winter Rental in Spain Like? - Soul Travelers 3",
                    "type": "organic",
                    "url": "http://www.soultravelers3.com/2009/11/whats-a-spain-winter-rental-like-extended-travel-digital-nomad-4hww-vacation-.html"
                },
                "63": {
                    "description": "Play golf courses in Spain and stay at award-winning golf hotels and resorts for great value prices. Read reviews from fellow golfers.",
                    "markup": 0,
                    "page_number": 6,
                    "rich_snippets": [],
                    "title": "Golf in Spain, Golf Holidays in Spain, Golf Breaks Spain",
                    "type": "organic",
                    "url": "http://www.golfbreaks.com/spain"
                },
                "64": {
                    "description": "Hello forum, We are a Canadian family looking to invest in an inexpensive property for vacations in Spain. Many Canadians still invest in ...",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Where to buy a vacation property in Spain? - Expat Forum",
                    "type": "organic",
                    "url": "http://www.expatforum.com/expats/spain-expat-forum-expats-living-spain/138078-where-buy-vacation-property-spain.html"
                },
                "65": {
                    "description": "Spain's best beach resorts at the Costa Brava in Catalonia, tourist information. ... Learn why it's a good idea to vacation in Spain this year. Continue reading →.",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Costa Brava Tourist Guide",
                    "type": "organic",
                    "url": "http://costabravatouristguide.com/"
                },
                "66": {
                    "description": "Spain was one of the first holiday destinations overseas that we flocked to in our masses, and the enduring popularity of cheap holidays to Spain shows no sign of stopping in 2016. So if you're looking for a discount holiday package we suggest you book early as popular resorts are ...",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Cheap Holidays to Spain | Compare Holidays | dealchecker ...",
                    "type": "organic",
                    "url": "http://www.dealchecker.co.uk/cheap-holidays/spain.html"
                },
                "67": {
                    "description": "Sunny Spain is an easy to reach destination with a great variety of horse riding holidays including point-to-point treks and beach riding.",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Finca Alcadeisa, horseback vacation Spain Unicorn Trails",
                    "type": "organic",
                    "url": "https://www.unicorntrails.com/europe/spain/fincaalcadeisa/"
                },
                "68": {
                    "description": "Discover great holiday deals to Spain with lastminute.com. With a fantastic range of holidays throughout Spain to choose from you'll be spoilt for choice.",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Spain Holidays | Cheap Spain Deals | lastminute.com",
                    "type": "organic",
                    "url": "http://www.lastminute.com/holidays/spain.html"
                },
                "69": {
                    "description": "Superb horse riding vacations in Spain for proficient riders. Join us for fantastic beach gallops and superb forest riding.",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Horse riding vacations in Spain with superb beach and ...",
                    "type": "organic",
                    "url": "http://www.fantasiaadventureholidays.com/horse_news.html"
                },
                "70": {
                    "description": "Holiday Rentals available directly from their owners in Spain, Europe choose from a huge selection of accommodations, including villas, apartments, condos ...",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Holiday Rentals by Owners in Spain, Europe Vacation Rental",
                    "type": "organic",
                    "url": "http://www.ownersrentals.com/search/Europe/Spain.html"
                },
                "71": {
                    "description": "We are one of the largest and most respected independent promoters of Holiday Ownership interests in Europe. Specialized in the commercial aspects and ...",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Diversified Vacation Ownership - Costa del Sol, Spain",
                    "type": "organic",
                    "url": "http://www.diversifiedresorts.com/vacation-ownership.php"
                },
                "72": {
                    "description": "Love Home Swap helps you find the ideal home exchange in Spain. Join the world's biggest home swap club and save up to 90% on travel costs.",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Home Exchange | Spain | Love Home Swap",
                    "type": "organic",
                    "url": "http://www.lovehomeswap.com/location/spain"
                },
                "73": {
                    "description": "You want to spend your next summer vacation in Spain in a rental holiday home, house, villa or apartment on the Costa Brava? For vacation rentals of holiday ...",
                    "markup": 0,
                    "page_number": 7,
                    "rich_snippets": [],
                    "title": "Search vacation property for holiday rentals in Spain, Costa ...",
                    "type": "organic",
                    "url": "http://www.immocostabrava.com/en/search-vacation-property-for-holiday-rentals-in-spain-costa-brava-villas-houses-apartments-flats-for-rent"
                },
                "74": {
                    "description": "Explore Spain's countryside with the best cycling routes in our self led and guided bike tours. ... This turned into the best vacation we've ever had, at any price.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Bicycle Touring Spain: The Best Spain Bike Tours",
                    "type": "organic",
                    "url": "http://www.cyclingcountry.com/CycleTours/Spain.htm"
                },
                "75": {
                    "description": "17 Jan 2014 - Some of you may wonder what Alexander Megos has been up to lately. So did I... well I knew he was on vacation in Spain, but no more than ...",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "UKC News - Alex Megos talks about his Spanish vacation",
                    "type": "organic",
                    "url": "http://www.ukclimbing.com/news/item.php?id=68654"
                },
                "76": {
                    "description": "The perfect villa for rental located in Ronda, Malaga, Andalucia, Spain. The White Olive is ... Vacation Rentals Spain | Farmhouse Ronda | Holiday Rentals Spain.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Villa for rental Ronda Malaga Spain | The White Olive ...",
                    "type": "organic",
                    "url": "http://www.thewhiteolive.com/"
                },
                "77": {
                    "description": "Self catering acommodation. Five bedroom holiday home, two bedroom and one bedroom cottage rental in the white villages of rural andalucia.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Self-catering vacation rentals in rural Andalucia Spain - Self ...",
                    "type": "organic",
                    "url": "http://www.vivasiesta.com/"
                },
                "78": {
                    "description": "Whether you're visiting for business or on vacation, you'll be impressed with our well-designed golfing packages. With a wide range of courses of every variety, ...",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Barcelona Golf: Golf in Spain | Golf Holidays in Spain",
                    "type": "organic",
                    "url": "http://www.barcelonagolf.com/"
                },
                "79": {
                    "description": "The best spa hotels, wellness breaks, health retreats & weight loss holidays. View our spa & hotel offers in Spain and Portugal.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Spa hotels Spain, wellness packages & weight loss holidays",
                    "type": "organic",
                    "url": "http://www.spa-in-spain.com/"
                },
                "80": {
                    "description": "Search the best beach holidays in Spain. Secure today with a low deposit. ATOL protected. Book now.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Cheap holidays to Spain | On the Beach",
                    "type": "organic",
                    "url": "https://www.onthebeach.co.uk/destinations/spain"
                },
                "81": {
                    "description": "7 May 2015 - FORGET Majorca and Tenerife, Greek holiday islands are the best in Europe, according to rankings based on a staggering 140 million ...",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.express.co.uk › Travel › Travel News"
                        }
                    ],
                    "title": "Forget Spain and Italy: Beautiful holiday islands of GREECE ...",
                    "type": "organic",
                    "url": "http://www.express.co.uk/travel/articles/575302/Forget-Spain-and-Italy-The-beautiful-holiday-islands-of-GREECE-are-best-in-Europe"
                },
                "82": {
                    "description": "GB Vacation rental · FR Location de vacances ... Find your ideal holiday rental in France, Corsica, Italy, Spain & Croatia. Duration of your stay, 7 nights. 7 nights.",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Holiday rentals in France, Corsica, Italy, Spain and Croatia ...",
                    "type": "organic",
                    "url": "http://www.odalys-vacation-rental.com/"
                },
                "83": {
                    "description": "Welcome Cottages - A part of the Wyndham Vacation Rentals® Family of Brands. Through Wyndham Vacation Rentals, we offer holidaymakers like you the ...",
                    "markup": 0,
                    "page_number": 8,
                    "rich_snippets": [],
                    "title": "Wyndham Vacation Rentals | Holiday cottages in the UK ...",
                    "type": "organic",
                    "url": "https://www.welcomecottages.com/info/wyndham-vacation-rentals"
                },
                "84": {
                    "description": "Art Vacations in Spain. Painting Holidays in Extremadura - SW Spain and Wales Beginners and experienced welcome. 7 nights : Stay in a Conquistador Palace, ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Holiday Artists - Art Vacations - Painting Holidays and Art ...",
                    "type": "organic",
                    "url": "http://www.holidayartists.com/painting.html"
                },
                "85": {
                    "description": "View photos from holiday makers on vacation in Spain. Spanish beaches, mountains, cities, resorts, ancient ruins, sights and more. All images captured by ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.360travelguide.com › Travel Guides › Europe › Spain"
                        }
                    ],
                    "title": "Spain Vacation Photos | Spanish Holiday Images & Travel ...",
                    "type": "organic",
                    "url": "http://www.360travelguide.com/Spain/images.asp"
                },
                "86": {
                    "description": "Albatros Villa, Your Next Holiday Home Rentals Villa In Spain, With Free Heated Pool, Pool Heating, Free wireless WiFi Internet, AirCon, Pool Table, Table ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Holidays | Holiday House | Vacation Rentals | Home | Spain ...",
                    "type": "organic",
                    "url": "http://www.albatrosvilla.com/"
                },
                "87": {
                    "description": "Wide choice of dancing holidays & vacations including salsa, flamenco, ... Learn Tango & Spanish in beautiful Granada, Spain, from €325 (5 days) ex flights.",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [
                        {
                            "guessed_type": "review",
                            "type": "rating",
                            "votes": 6,
                            "score": 5,
                            "raw": " Rating: 5 - ‎6 reviews"
                        }
                    ],
                    "title": "Dancing holidays. Dancing vacations & holidays. World's ...",
                    "type": "organic",
                    "url": "http://www.responsibletravel.com/holidays/dancing"
                },
                "88": {
                    "description": "55 results - Stunning Luxury Villas in Spain from Abercrombie & Kent. ... predictability of the summer weather ensures your villa vacation lives long in the memory.",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Luxury Villas In Spain, Luxury Spanish Villas - A&K Villas",
                    "type": "organic",
                    "url": "http://www.akvillas.com/luxury-villas-spain/"
                },
                "89": {
                    "description": "Everything you need to know about galicia in spain's green northern region ... are often promoted as the areas main vacation attractions, beautiful beaches fill ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "GALICIA SPAIN | Galicia Guide",
                    "type": "organic",
                    "url": "http://www.galiciaguide.com/Galicia-index.html"
                },
                "90": {
                    "description": "12 Jan 2016 - Pack your vacation capsule wardrobe for Spain with the complete guide from What to Wear On Vacation. Don't know what to take? Fed up with ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "What to Wear in Spain: Packing checklists and clothing tips ...",
                    "type": "organic",
                    "url": "http://www.whattowearonholiday.com/us/destinations/europe/spain/66-what-to-wear-in-spain.php"
                },
                "91": {
                    "description": "3 Bedroom, 2 bath Self Catering Holiday Rental Apartment in La Cala de Mijas, Spain. Rent our holiday house today!",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Spanish Vacation Rental - 3 Bedroom Holiday Rental ...",
                    "type": "organic",
                    "url": "http://www.spanishvacationrental.com/"
                },
                "92": {
                    "description": "The premier online guide for useful information about Andalucia and Southern Spain since 1996.",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Premier online guide for useful information about Andalucia ...",
                    "type": "organic",
                    "url": "http://www.andalucia.com/"
                },
                "93": {
                    "description": "Oxygen Vacation Spain: Spain is a very popular destination for holiday makers in need of medical oxygen. The wide variaty of equipment and a thorough ...",
                    "markup": 0,
                    "page_number": 9,
                    "rich_snippets": [],
                    "title": "Oxygen Vacation Spain - Oxygenworldwide",
                    "type": "organic",
                    "url": "http://oxygenworldwide.com/en/help/wiki/121-oxygen-vacation-spain.html"
                },
                "94": {
                    "description": "Large selection of affordable holiday rentals Spain vacation rentals Spain and worldwide. Owners advertise for free!",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "holiday rental Spain vacation rental Spain",
                    "type": "organic",
                    "url": "http://www.holiday-rentals-worldwide.co.uk/auswobj_e.aspx?Country=ES"
                },
                "95": {
                    "description": "Holiday Villas rentals in Mijas, Costa del Sol, Information on Golfing in Mijas, Spain.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Villas in Mijas Property, Holiday, Vacation Rentals, Costa ...",
                    "type": "organic",
                    "url": "http://www.villasinmijasspain.com/"
                },
                "96": {
                    "description": "Planning on visiting Spain with your baby? Check out our complete guide to family holidays in Spain, including information on food, travel and healthcare.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Family holidays in Spain - BabyCentre",
                    "type": "organic",
                    "url": "http://www.babycentre.co.uk/a554507/family-holidays-in-spain"
                },
                "97": {
                    "description": "The Spain of a million wish-you-were-here postcards, the Balearic Islands have all the sun and sea attributes to write home about. But there is...",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [
                        {
                            "type": "breadcrumb",
                            "path": "www.lonelyplanet.com › Europe › Mediterranean Europe › Spain"
                        }
                    ],
                    "title": "Mallorca, Menorca & Ibiza, Spain - Lonely Planet",
                    "type": "organic",
                    "url": "http://www.lonelyplanet.com/spain/balearic-islands"
                },
                "98": {
                    "description": "Horseback riding vacations in Spain! Enquire about our ONE OFF exploring trek “Riding Home from Ronda” April 21st -25th 2016. Ride Andalucia is a specialist ...",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Ride Andalucia - Horseback riding holidays in southern Spain",
                    "type": "organic",
                    "url": "http://rideandalucia.com/"
                },
                "99": {
                    "description": "Castle vacation tips, plans and strategies for history enthusiasts visiting Europe. ... Germany, Spain or Austria, and discover some magnificent castles en route.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Castle Vacations: Unforgettable Vacation Trips To Castles in ...",
                    "type": "organic",
                    "url": "http://www.exploring-castles.com/castle_vacations.html"
                },
                "100": {
                    "description": "If you're looking for a Vacation Rentals in Puerto Pollensa (Mallorca), then the team at Balearic Villas have all the local knowledge, and fantastic properties, you ...",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Vacation Rentals in Puerto Pollensa, Spain | by Balearic ...",
                    "type": "organic",
                    "url": "https://www.balearic-villas.com/vacation-rentals-in-puerto-pollensa-spain-19-54.html"
                },
                "101": {
                    "description": "Explore Spain with Rough Guides: find out the best places to visit, when to go, view itineraries and read about Barcelona, flamenco, tapas and Semana Santa.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Places to Visit in Spain | Spain Travel Guide | Rough Guides",
                    "type": "organic",
                    "url": "http://www.roughguides.com/destinations/europe/spain/"
                },
                "102": {
                    "description": "A guide to vacations, travel, and hotels in Madrid, Madrid, Spain.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Destination Traveler: Spain - vacation, travel, hotels in ...",
                    "type": "organic",
                    "url": "http://www.destination-traveler.com/spain/regions/madrid/madrid.asp"
                },
                "103": {
                    "description": "Agency representing several schools in Spain and Latin America.",
                    "markup": 0,
                    "page_number": 10,
                    "rich_snippets": [],
                    "title": "Study Spanish language courses in Spain, Cuba, Latin ...",
                    "type": "organic",
                    "url": "http://www.spanishstudyholidays.com/"
                }
            },
            "video": {}
        },
        "summary": {
            "global": {
                "ad": 30,
                "image": 4,
                "news": 0,
                "organic": 99,
                "place": 0,
                "shopping": 0,
                "total": 13100000,
                "video": 0
            },
            "pages": {
                "1": {
                    "ad": 3,
                    "image": 0,
                    "news": 0,
                    "organic": 10,
                    "place": 0,
                    "shopping": 0,
                    "video": 0
                },
                "2": {
                    "ad": 2,
                    "image": 4,
                    "news": 0,
                    "organic": 9,
                    "place": 0,
                    "shopping": 0,
                    "video": 0
                },
                "3": {
                    "ad": 2,
                    "image": 0,
                    "news": 0,
                    "organic": 10,
                    "place": 0,
                    "shopping": 0,
                    "video": 0
                },
                "4": {
                    "ad": 3,
                    "image": 0,
                    "news": 0,
                    "organic": 10,
                    "place": 0,
                    "shopping": 0,
                    "video": 0
                },
                "5": {
                    "ad": 3,
                    "image": 0,
                    "news": 0,
                    "organic": 10,
                    "place": 0,
                    "shopping": 0,
                    "video": 0
                },
                "6": {
                    "ad": 3,
                    "image": 0,
                    "news": 0,
                    "organic": 10,
                    "place": 0,
                    "shopping": 0,
                    "video": 0
                },
                "7": {
                    "ad": 3,
                    "image": 0,
                    "news": 0,
                    "organic": 10,
                    "place": 0,
                    "shopping": 0,
                    "video": 0
                },
                "8": {
                    "ad": 5,
                    "image": 0,
                    "news": 0,
                    "organic": 10,
                    "place": 0,
                    "shopping": 0,
                    "video": 0
                },
                "9": {
                    "ad": 3,
                    "image": 0,
                    "news": 0,
                    "organic": 10,
                    "place": 0,
                    "shopping": 0,
                    "video": 0
                },
                "10": {
                    "ad": 3,
                    "image": 0,
                    "news": 0,
                    "organic": 10,
                    "place": 0,
                    "shopping": 0,
                    "video": 0
                }
            }
        }
    }
}
```

