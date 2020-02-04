## Overview

**Long short-term memory** (**LSTM**) is well-suited to [classifying](https://en.wikipedia.org/wiki/Classification_in_machine_learning), [processing](https://en.wikipedia.org/wiki/Computer_data_processing) and [making predictions](https://en.wikipedia.org/wiki/Predict) based on [time series](https://en.wikipedia.org/wiki/Time_series) data, since there can be lags of unknown duration between important events in a time series.

So I predicted Samsung Electronics' closer stock price with LSTM networks for practice.

<br />

## Discussion

I could check ensemble model (kospi dataset + samsung dataset) is more accurate than single input model which is used input layer with only stock data of samsung electronics.

If I had more datasets of older stock price information and some other corporations that is same field with Samsung Electronics, predicted close price could be more accurate.