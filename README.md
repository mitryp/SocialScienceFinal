# Telegram Exploratory Data Analysis (EDA)

The Jupyter Notebook in this repo conducts an EDA on private messages and chat catalogue data exported from Telegram. The analysis covers various aspects, including message patterns, user behaviour, and anomalies, utilizing various visualization tools from `pandas` and `matplotlib`.

## Getting Started

To use this Notebook, you will need to have the messages and dialogues from Telegram in CSV format. 

To get them, you can use the scripts from [Ilya Stasiuk/telegram-data-collection](https://github.com/IlyaStasiuk/telegram-data-collection), the author of which did a great job fixing and optimizing the [original code by SanGreel](https://github.com/SanGreel/telegram-data-collection). 

However, due to the unavailability of the fork at the time this analysis was originally performed, the messages were exported using the Telegram Desktop export to JSON functionality and a custom [JSON to CSV parser](). To ensure all the logic stays intact, I recommend using this approach. If using this approach, you still need to download your dialogue data using the [0_download_dialogs_list.py](https://github.com/IlyaStasiuk/telegram-data-collection/blob/master/0_download_dialogs_list.py) script.

After downloading your data using any of the methods above, you will need to merge it using [this Notebook by SanGreel](https://github.com/SanGreel/telegram-dialogs-analysis-v2/blob/main/0_merge_data.ipynb), which is quite straightforward.

After this is done, you can launch the Notebook from this repository and follow along with its documentation, executing cells one by one.

> Note that the execution order is important, as many tasks reuse the data from the previous cells.

## Customization

Feel free to customize the notebook based on your specific analysis goals. Modify code sections, add new visualizations, and adapt the analysis to your dataset as needed.

## Contributing

Contributions are welcome! If you find any issues or want to improve my work, please open an issue and create a pull request.