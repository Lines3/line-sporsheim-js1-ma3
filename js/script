// question 1

const getRemainder = (a, b) => a % b;

//const result = getRemainder(5, 2);

//console.log(result);


//question 2

const url = "https://api.rawg.io/api/games?dates=2019-01-01,2019-12-31&ordering=-rating&key=64c0a276897e4b5dbf0dea189ebfca2e";

const resultsContainer = document.querySelector(".results");

console.log(fetch(url));

async function GetInfo() {

    try {
        const response = await fetch(url);

        const name = await response.json();

        const rating = await response.json();

        const tags = await response.json();

        const results = await response.json();

        console.log(results);

        resultsContainer.innerHTML = "";

        for (let i = 0; i < length; i++) {

            if (i === 8) {
                break;
            }
        }
        resultsContainer.innerHTML += `<div class="results">$(name[i].text)</div>}`;
    }
    catch (error) {
        resultsContainer.innerHTML = "Apologies, an error occured";
    }

}

GetInfo();

//How do I know what the attributes in the API-database are called, where do I find that information? Is it correct to call it tags or does it need to be a specific name for it?
