# LIFI_TASK

This repository contains a Python script that interacts with the LI.FI API to fetch quotes for swapping 1,000 USDC from all supported chains to USDT on all other supported chains. The script performs the following tasks:
Task 1: Fetching Quotes for Token Swapping

The script queries the LI.FI API to retrieve quotes for swapping 1,000 USDC from each supported chain to USDT on all other supported chains. It covers all permutations to ensure comprehensive coverage.
Task 2: Calculating Costs and Sorting

After obtaining the quotes, the script calculates the costs incurred by the user, including gas fees. It then sorts the costs in descending order to provide insights into the expenses associated with the token swapping process.
Task 3: Analyzing Bridge Recommendations

The script analyzes the recommendations for bridges. It generates a count of how many times a bridge is recommended and how many times no bridge is recommended. This analysis helps evaluate the suitability and frequency of different bridges, such as Connext, in the token swapping process.
Requirements

    Python 3
    requests library

Usage

Install the required dependencies using the following command:

    pip install requests

Open the Python script in a Python IDE or editor.

Execute the script to fetch quotes, calculate costs, and analyze bridge recommendations.

The script will display the sorted costs in descending order, the count of bridge recommendations, and the count of no bridge recommendations.

For more information about the LI.FI API, refer to the [LI.FI API documentation](https://li.quest/documentation).
