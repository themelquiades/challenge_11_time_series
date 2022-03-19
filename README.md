# Analyzing MercadoLibre's Popularity with Time Series Analysis
Week 11 Challenge, analyzing MercadoLibre's stock performance and search traffic to uncover correlations and predict future results.

The analysis concluded the following:

- Google search traffic increased by 8.55% in March 2020, when MercadoLibre announced its financial results

- Search traffic tends to be the highest from 22:00 GMT through 01:00 GMT on most days. However, Saturday seems to have search traffic more conentrated right around 0:00 GMT while it is relatively lower throughout the rest of the day

- Search traffic increases sharply from mid-October through Christmas, but then drops off between Christmas and New Year's week. Search traffic then increases even more between mid-January and the end of February

- Consistent with the rest of the industry, MercadoLibre price fell sharply through March 2020 and the beginning of April 2020, but then recovered and appreciated greatly through May and June 2020. Search traffic seemed to get more volatile in mid-March 2020 and then fall sharply until mid-April 2020. It then seemed to recover fairly well in May and June.

- There doesn't appear to be a predictable relationship between search trends and stock volatility or search trends and price movement. There's a slightly significant negative correlation between stock volatility and the lagged search trends (-0.14), but very little correlation between lagged search trends and hourly stock return (0.2).

- Our Prophet model predicts that interest in MercadoLibre will fade over the next 80 days

- Search traffic tends to be highest on Tuesdays compared to other days of the week and right around 0:00 GMT each day. Search traddic tends to drop sharply in Mid-October each year.

All analysis was done using Google Colab.

## Contributors

This analysis was created by Nico Cortese with support from the lovely Fintech Coding Boot Camp Team at Boot Camp Spot / Columbia School of Engineering

Nico Cortese

XXX-XXX-XXXX

XXXX@gmail.com

---

## License

MIT License

Copyright (c) 2022 NicoCortese

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.