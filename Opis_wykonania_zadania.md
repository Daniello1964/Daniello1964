Importujemy moduł node-fetch, który umożliwia wykonywanie zapytań HTTP z poziomu Node.js.
javascript

Tworzymy funkcję main, która będzie główną funkcją programu. W funkcji tej wywołujemy trzy zapytania HTTP do API fakestoreapi.com w celu pobrania danych użytkowników, koszyków i produktów.
javascript

Obliczamy wartości produktów dla każdej kategorii. Tworzymy pusty obiekt categoryValues, który będzie przechowywał sumy wartości produktów dla każdej kategorii. Następnie iterujemy po wszystkich produktach i dodajemy ich wartość do sumy dla odpowiedniej kategorii.

Znajdujemy koszyk z najwyższą wartością i wyświetlamy jego wartość i nazwę właściciela. Iterujemy po wszystkich koszykach i dla każdego koszyka wyliczamy wartość jego zawartości, czyli sumę wartości wszystkich produktów w koszyku. Jeśli wartość ta jest większa niż wartość koszyka z maksymalną wartością dotychczas znalezioną, to aktualizujemy wartość maksymalną i nazwę właściciela koszyka Znajdujemy dwóch użytkowników, którzy mieszkają najdalej od siebie i wyświetlamy ich nazwy i odległość między nimi. Iterujemy po wszystkich parach użytkowników i dla każdej pary wyliczamy odległość między ich adresami, korzystając ze wzoru Haversine. Jeśli odległość ta jest większa niż dotychczas znaleziona maksymalna odległość, to aktualizujemy maksymalną odległość i nazwy użytkownik.
