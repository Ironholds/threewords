## An R client library for what3words

__Author:__ Oliver Keyes<br/>
__License:__ [MIT](http://opensource.org/licenses/MIT)<br/>
__Status:__ Stable

[what3words](http://what3words.com/) is a service that divides the world into 3m by 3m geographic squares, each represented by a unique cluster of three words. This allows for the convenient and memorable representation of small areas. `threewords` is an R client for the what3words API, allowing you to convert latitude/longitude pairs into word sequences, or word sequences back into pairs.

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.

### Installation

To grab it from CRAN:

    install.packages("threewords")
    
For the development release:

    devtools::install_github("ironholds/threewords")