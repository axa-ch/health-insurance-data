# Swiss health insurance data

## List of Swiss health insurers

### Download

* [.json](insurers.json)

### Structure

Field|Description|
--|--|
`id`|Unique id given by the Federal Office of Public Health (FOPH)|
`name`|Name of the insurance company|
`location`|Location of the insurance company|
`dailySicknessBenefitsInsuranceOnly`|If `true`, indicates that only daily sicknes benefits insurance is offered|

### Source

Extracted from
[the list of approved health insurers](https://www.bag.admin.ch/dam/bag/de/dokumente/kuv-aufsicht/rakv/krankenkassen-verzeichnis.pdf.download.pdf/krankenkassen-verzeichnis.pdf)
by the [Federal Office of Public Health (FOPH)](https://www.bag.admin.ch/bag/en/home.html).
