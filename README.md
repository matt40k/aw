# AdultWork.com UK Profile data dump
[![License: Open Data Commons Attribution](https://img.shields.io/badge/License-ODC_BY-brightgreen.svg)](https://opendatacommons.org/licenses/by/) [![CSV Validation](https://csvlint.io/validation/59f23a8f91006e0004000018.svg)](https://csvlint.io/validation/59f23a8f91006e0004000018)

Data is extracted from AdultWork.com via the [Developer API](https://developers.adultwork.com/en-GB/Site/API/Reference). The extracted data is then exported to CSV and committed to this Git repo. The Extraction is done on a "best endeavors" bases. The extract is scheduled to occur every 5 hours. Previous versions can be accessed via the Git history, previous versions are listed in the datapackage.json. Only UK profiles are extracted. Profiles are only for people who are providing services.

# About AdultWork.com
AdultWork.com is an online directory of adult service providers and a virtual meeting place for those offering and seeking such services.

AdultWork.com is run by its members. We provide these members with a platform and a suite of tools for them to conduct and market their own adult businesses.

Members offering services create accounts and maintain their own profiles. Through their profiles, they can advertise the services they provide and arrange webcam, telephone or SMS conversations; take escort bookings, and sell photographs, movies and other erotica.

Members who are seeking services also create accounts and can leave ratings of and feedback about their experiences. Members cannot offer or purchase services without creating an account.

All online purchases are made in AdultWork.com credits. Various methods of purchasing credits are available: including credit card payments, bank transfers and exchange of prepaid vouchers.

AdultWork.com does not accept payment for any escort-related activity and anyone found to be misusing the payment mechanisms to do so will have their membership terminated permanently.

# About the datapackage.json
Data is stored as CSV. This gives the following benefits:

>>
>> - **Simplicity**: CSV is incredibly simple - perhaps the simplest structured data format there is
>> - **Openness**: the CSV ‘standard’ is well-known and open - free for anyone to use
>> - **Easy to use**: CSV is widely supported - practically every spreadsheet program, relational database and programming language in existence can handle CSV in some form or other
>> - **Hackable**: CSV is text-based and therefore amenable to manipulation and access from a wide range of standard tools (including revision control systems such as git, mercurial and subversion)
>> - **Big or small**: CSV files can range from under a kilobyte to gigabytes and its line-oriented structure mean it can be incrementally processed – you do not need to read an entire file to extract a single row.
>>
[Reference](https://rufuspollock.com/2014/05/05/csv-conf-2014-for-data-makers-everywhere/)

However CSV lacks certain metadata that makes automation difficult. Data Package looks to address this by by storing that metadata in a separate json file. [More info](https://specs.frictionlessdata.io/data-package/).
