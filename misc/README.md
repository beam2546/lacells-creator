# lacells database

This Github repository contains database of cell tower locations that can be used for offline positioning on Android devices. The data is intended to be used with [Local GSM Backend](https://gitlab.com/deveee/Local-GSM-Backend) (one of the backend for [µg’s UnifiedNLP](https://github.com/microg/UnifiedNlp)) but can also be used for other purpose.

This repository will update every day at 02:00 UTC time.

## How to use in Local GSM Backend

Go to "Advanced Settings" then put the following URL to lacells Custom URL

`https://raw.githubusercontent.com/beam2546/lacells/main/lacells-countries.csv`

## License

This data is provided under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/). Please refer to the LICENSE file for more details.

## Credits

The data is aggregated from both [Mozilla Location Service](https://location.services.mozilla.com/) and [OpenCellID](https://opencellid.org/). The license for these datasets are [public domain](https://creativecommons.org/publicdomain/zero/1.0/) and [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) respectively. By releasing this dataset under the terms of the CC-BY-SA 4.0 license, the terms of both source licenses are met.

The tool that being used to generated this database is the [forked version](https://github.com/beam2546/lacells-creator) of lacells-creator. The license for these tool is [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html).

Many of the wordings and the structure of this README file is taken from [wvengen's lacells repository](https://github.com/wvengen/lacells).