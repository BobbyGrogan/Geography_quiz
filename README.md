# Geography_quiz

countries = [
    ["Cambodia", "Phnom Penh", 16500000],
    ["Paraguay", "Asuncion", 7000000],
    ["Finland", "Helsinki", 5500000],
    ["Comoros", "Moroni", 850000],
    ["Cote d'Ivoire", "Abidjan", 26000000],
    ["Madagascar", "Antananarivo", 27000000],
    ["Austria", 'Vienna', 8900000],
    ["Italy", "Rome", 60000000],
    ["Israel", "Jerusalem", 9000000],
    ["Ireland", "Dublin", 4900000],
    ["Iraq", "Baghdad", 39000000],
    ["Iran", "Tehran", 83000000],
    ["Indonesia", "Jakarta", 270000000],
    ["Iceland", "Reykjavik", 360000],
    ["Guinea-Bissau", "Bissau", 1900000],
    ["Guinea", "Conakry", 13000000],
    ["Grenada", "Saint George's", 110000],
    ["Greece", "Athens", 10700000],
    ["Ghana", "Accra", 31000000],
    ["Germany", "Berlin", 83000000],
    ["Georgia", 'Tbilisi', 4000000],
    ["The Gambia", "Banjul", 2400000],
    ["Gabon", "Libreville", 2200000],
    ["France", "Paris", 67000000],
    ["Fiji", "Suva", 890000],
    ["Ethiopia", "Addis Ababa", 112000000],
    ["Estonia", "Tallinn", 1300000],
    ["Eritrea", "Asmara", 3200000],
    ["Equatorial Guinea", "Malabo", 1400000], #soon new capital
    ["El Salvador", "San Salvador", 6500000],
    ["Egypt", "Cairo", 100000000],
    ["Ecuador", "Quito", 174000000],
    ["Dominican Republic", "Santo Domingo", 10700000],
    ["Djibouti", "Djibouti", 980000],
    ["Dominica", "Roseau", 72000],
    ["Denmark", "Copenhagen", 5800000],
    ["Curacao", "Willemstad", 160000],
    ["Czechia", "Prague", 10700000],
    ["Cyprus", "Nicosia", 880000],
    ["Cuba", "Havana", 11300000],
    ["Croatia", "Zagreb", 4100000],
    ["The Bahamas", "Nassau", 390000],
    ["Costa Rica", "San Jose", 5100000],
    ["The Congo", 'Brazzaville', 5400000],
    ["The Democratic Republic of the Congo", "Kinshasa", 87000000],
    ["South Korea", "Seoul", 52000000],
    ["Mauritania", "Nouakchott", 4500000],
    ["Mauritius", "Port Louis", 1300000],
    ["Mexico", "Mexico City", 128000000],
    ["Federated States of Micronesia", "Palikir", 114000],
    ["Moldova", "Chisinau", 2600000],
    ["Monaco", "Monaco", 39000],
    ["Mongolia", "Ulaanbaatar", 3200000],
    ["Montenegro", "Podgorica", 6200000], #and Cetinje
    ["Morocco", "Rabat", 37000000],
    ["Mozambique", "Maputo", 30500000],
    ["Namibia", "Windhoek", 2500000],
    ["Nauru", "Yaren", 12600],
    ["Nepal", "Kathmandu", 28600000],
    ["Netherlands", "Amsterdam", 17300000], #and the Hague
    ["New Zealand", "Wellington", 4900000],
    ["Guatemala", "Guatemala City", 16500000],
    ["Mali", "Bamako", 20000000],
    ["North Korea", "Pyongyang", 25700000],
    ["Switzerland", "Bern", 8500000], #though techically none
    ["China", "Beijing", 1400000000],
    ["Angola", "Luanda", 32000000],
    ["Andorra", "Andorra la Vella", 77000],
    ["Algeria", "Algiers", 43000000],
    ["Albania", "Tirana", 2850000],
    ["Afghanistan", "Kabul", 38000000],
    ["Argentina", "Buenos Aires", 45000000],
    ["Armenia", "Yerevan", 2960000],
    ["Liberia", "Monrovia", 4950000],
    ["Malaysia", "Kuala Lumpur", 32000000],
    ["Malawi", "Lilongwe", 19000000],
    ["Papua New Guinea", "Port Moresby", 8800000],
    ["Panama", "Panama City", 4300000],
    ["Azerbaijan", "Baku", 10000000],
    ["Australia", "Canberra", 25400000],
    ["Myanmar", "Naypidaw", 54000000],
    ["Bhutan", "Thimphu", 760000],
    ["Nicaragua", "Managua", 6600000],
    ["Bangladesh", "Dhaka", 163000000],
    ["Bahrain", "Manama", 1640000],
    ["Burundi", "Gitega", 11500000],
    ["Burkina Faso", "Ouagadougou", 20500000],
    ["Bulgaria", "Sofia", 7000000],
    ["Brunei", "Bandar Seri Begawan", 430000],
    ["Botswana", "Gaborone", 2300000],
    ["Bosnia and Herzegovina", "Sarajevo", 3300000],
    ["Bolivia", "La Paz", 11500000], #Sucre also
    ["Belize", "Belmopan", 390000],
    ["Belgium", "Brussels", 11500000],
    ["Belarus", "Minsk", 9500000],
    ["Barbados", "Bridgetown", 290000],
    ["Benin", "Porto-Novo", 11800000],
    ["Eswatini", "Lobamba", 1150000], #Mbabane also
    ["Syria", "Damascus", 17000000],
    ["Honduras", "Tegucigalpa", 9800000],
    ["Holy See", "Vatican City", 825],
    ["Haiti", "Port-au-Prince", 11300000],
    ["Guyana", "Georgetown", 790000],
    ["Hungary", "Budapest", 9800000],
    ["Jordan", "Amman", 10100000],
    ["East Timor", "Dili", 1300000], #aka Timor-Leste
    ["Taiwan", "Taipei", 2360000],
    ["Tajikistan", "Dushanbe", 9300000],
    ["India", "New Delhi", 1370000000],
    ["Palau", "Ngerlmud", 18000],
    ["Pakistan", "Islamabad", 217000000],
    ["Oman", "Muscat", 5000000],
    ["Norway", "Oslo", 5300000],
    ["Nigeria", "Abuja", 201000000],
    ["Niger", "Niamey", 23300000],
    ["Tanzania", "Dodoma", 58000000], # but also Dar es Salaam
    ["Thailand", "Bangkok", 69700000],
    ["Togo", "Lome", 8100000],
    ["Tonga", "Nuku'alofa", 105000],
    ["Trinidad and Tobago", "Port-of-Spain", 1400000],
    ["Tunisia", "Tunis", 11700000],
    ["Turkey", "Ankara", 82000000],
    ["Turkmenistan", "Ashgabat", 6000000],
    ["Tuvalu", "Funafuti", 11700],
    ["Uganda", "Kampala", 44500000],
    ["Ukraine", "Kiev", 44500000],
    ["United Arab Emirates", "Abu Dhabi", 9800000],
    ["United Kingdom", "London", 66500000],
    ["United States of America", "Washington DC", 330000000],
    ["Uruguay", "Montevideo", 3500000],
    ["Uzbekistan", "Tashkent", 34000000],
    ["Vanuatu", "Port-Vila", 300000],
    ["Venezuela", "Caracas", 28500000],
    ["Vietnam", "Hanoi", 96500000],
    ["Yemen", "Sana'a", 29000000], #temporarily Aden
    ["Zambia", "Lusaka", 17900000],
    ["Zimbabwe", "Harare", 14700000],
    ["Sweden", "Stockholm", 10000000],
    ["Suriname", "Paramaribo", 580000],
    ["Sudan", "Khartoum", 43000000],
    ["Sri Lanka", "Colombo", 22000000], #also Sri Jayawardenepura Kotte
    ["Spain", "Madrid", 47000000],
    ["South Africa", "Pretoria", 59000000], #and Capetown and Bloemfontein
    ["South Sudan", "Juba", 11000000],
    ["Somalia", "Mogadishu", 11500000],
    ["Solomon Islands", "Honiara", 670000],
    ["Slovenia", "Ljubljana", 2100000],
    ["Slovakia", "Bratislava", 5450000],
    ["Singapore", "Singapore", 5700000],
    ["Sierra Leone", "Freetown", 7800000],
    ["Seychelles", "Victoria", 98000],
    ["Serbia", "Belgrade", 6950000],
    ["Senegal", "Dakar", 16500000],
    ["Saudi Arabia", "Riyadh", 34300000],
    ["Sao Tome and Principe", "Sao Tome", 215000],
    ["San Marino", "San Marino", 34000],
    ["Samoa", "Apia", 197000],
    ["Saint Vincent and the Grenadines", "Kingstown", 111000],
    ["Saint Lucia", "Castries", 183000],
    ["Saint Kitts and Nevis", "Basseterre", 53000],
    ["Rwanda", "Kigali", 12650000],
    ["Russia", "Moscow", 144500000],
    ["Romania", "Bucharest", 19400000],
    ["Qatar", "Doha", 2800000],
    ["Portugal", "Lisbon", 10300000],
    ["Poland", "Warsaw", 38000000],
    ["Philippines", "Manilla", 108000000],
    ["Peru", "Lima", 32500000],
    ["Marshall Islands", "Majuro", 39000],
    ["Malta", "Valletta", 503000],
    ["Maldives", "Male", 531000],
    ["North Macedonia", "Skopje", 2100000],
    ["Luxembourg", "Luxembourg City", 614000],
    ["Lithuania", "Vilnius", 2800000],
    ["Liechtenstein", "Vaduz", 38400],
    ["Libya", "Tripoli", 6800000],
    ["Lesotho", "Maseru", 2100000],
    ["Lebanon", "Beirut", 6850000],
    ["Latvia", "Riga", 1900000],
    ["Laos", "Vientiane", 7200000],
    ["Kyrgyzstan", "Bishkek", 6500000],
    ["Kuwait", "Kuwait City", 4200000],
    ["Kosovo", "Pristina", 1900000],
    ["Kiribati", "South Tarawa", 118000],
    ["Kenya", "Nairobi", 53000000],
    ["Kazakhstan", "Nur-Sultan", 18500000],
    ["Japan", "Tokyo", 126000000],
    ["Jamaica", "Kingston", 2950000],
    ["Antigua and Barbuda", "Saint John's", 97000],
    ["Cameroon", "Yaounde", 26000000],
    ["Central African Republic", "Bangui", 4800000],
    ["Cape Verde", "Praia", 550000],
    ["Canada", "Ottawa", 37600000],
    ["Brazil", "Brasilia", 211000000],
    ["Colombia", "Bogota", 50500000],
    ["Chad", "N'Djamena", 16000000],
    ["Chile", "Santiago", 19000000]
]

letters_list = ["A", "B", "C", "D", "E", "F", "G", "H", "I", "J", "K", "L", "M", "N", "O", "P",
                "Q", "R", "S", "T", "U", "V", "W", "X", "Y", "Z"]


def capital_quiz(rounds, dataset=countries):
    rounds_run = 0
    correct = 0
    used_list = []
    while rounds > rounds_run:
        random_country = rn.randint(0, len(dataset)-1)
        if random_country not in used_list:
            print(dataset[random_country][0])
            guess = (input("Guess the capital: ")).upper()
            rounds_run += 1
            if guess == dataset[random_country][1].upper():
                print("Correct Guess!")
                print()
                correct += 1
            else:
                print("Incorrect Guess! The answer is " + dataset[random_country][1])
                print()
    score = round(((correct/rounds_run) * 100), 2)
    print("You got " + str(score) + "% correct")


def population_quiz(rounds, leeway=0.5, dataset=countries):
    rounds_run = 0
    correct = 0
    used_list = []
    while rounds > rounds_run:
        random_country = rn.randint(0, len(dataset) - 1)
        if random_country not in used_list:
            print(dataset[random_country][0])
            used_list.append(random_country)
            guess = int((input("Population Guess: ")))
            answer = dataset[random_country][2]
            upper_bound = answer * (1 + leeway)
            lower_bound = answer * (1 - leeway)
            difference = abs(round((((guess - answer) / answer)*100), 2))
            rounds_run += 1
            if lower_bound <= guess <= upper_bound:
                    print("Correct Guess! The answer is " + str(dataset[random_country][2]))
                    print("You were " + str(difference) + "% away")
                    print()
                    correct += 1
            else:
                print("Incorrect Guess! The answer is " + str(dataset[random_country][2]))
                print("You were " + str(difference) + "% away")
                print()
    score = round(((correct / rounds_run) * 100), 2)
    print("You got " + str(score) + "% correct")


def capital_multiple_choice(rounds, num_options, dataset=countries, letters=letters_list):
    rounds_run = 0
    correct = 0
    used_list = []
    while rounds_run < rounds:
        choices_list = []
        country_int = rn.randint(0, len(dataset)-1)
        if country_int not in used_list:
            used_list.append(country_int)
            country_name = dataset[country_int][0]
            print("What is the capital of " + str(country_name) + "?")
            option_num = 0
            while len(choices_list) < num_options:
                new_choice = rn.randint(0, len(dataset)-1)
                if new_choice not in choices_list:
                    choices_list.append(dataset[new_choice][1])
                    option_num += 1
            which_replace = rn.randint(0, len(choices_list)-1)
            choices_list[which_replace] = dataset[country_int][1]
            letta = 0
            for choice in choices_list:
                print(letters[letta] + ".  " + str(choice))
                letta += 1
            guess = input("Your guess: ").upper()
            correct_guess = letters[which_replace]
            if guess == correct_guess:
                print("Correct Guess!")
                print()
                correct += 1
            else:
                print("Incorrect Guess! The answer is " + dataset[country_int][1])
                print()
            rounds_run += 1
    print("You got " + str(correct) + "/" + str(rounds_run))
