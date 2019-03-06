<!-- using System;
using System.Collections.Generic;

namespace data_lists_dictionaries
{
    class DataChallenge
    {
        static void Main(string[] args)
        {
            /*
                Create three dictionaries:
                - Dictionary one will contain Key: people, Value: FavMovies
                - Dictionary two will contain K: people, V: FavFoods
                - Dictionary three will be named "Favorite Things" and will contain K: person's name, V: A list containing the values from Dictionaries one and two.

                    1. Set up dicts. 1 and 2
                    2. Set up dict. 3 and loop

            */

            /*
                Dict. 1: People and FavMovies
            */

            Dictionary<string, string> MovieFavorites = new Dictionary<string, string>() {
                {"Hannah", "Django Unchained"},
                {"Kristen", "Beauty and the Beast"},
                {"Brian", "Galaxy Quest"},
                {"Evan", "All-Things Quentin Tarantino"},
                {"Brenda", "Rocky Horror"},
                {"Sarah", "Les Miserables"}
            };

            /*
                Dict. 2: People and FavFoods

                    Two ways of doing this:
                        - Option 1: Add items exactly as with list 1, or
                        - Option 2: Loop through dict 1 and for each key in dict 1, re-create that key in dict 2 with a new food value
                            - If you had a huge dictionary, option 2 would be the way to go.
                            - See: https://www.dotnetperls.com/copy-dictionary
            */

            Dictionary<string, string> FoodFavorites = new Dictionary<string, string>() {
                {"Hannah", "Cadbury Chocolate"},
                {"Kristen", "Mexican Food"},
                {"Brian", "Hot Chicken"},
                {"Evan", "Barbecued Ribs"},
                {"Brenda", "Chips"},
                {"Sarah", "Vegetarian Pizza"}
            };

            /*
                Dict. 3: Key: Person's name, Value: List: Dict. 1, Dict. 2 Values
            */

                Dictionary<string, List<string>> FavoriteThings = new Dictionary<string, List<string>>();
                    foreach (string key in MovieFavorites.Key)
                {
                    
                }


        }
    }
}
 -->
