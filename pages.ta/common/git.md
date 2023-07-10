# git

> விநியோகிக்கப்பட்ட பதிப்பு கட்டுப்பாட்டு அமைப்பு.
> `commit`, `add`, `branch`, `checkout`, `push`போன்ற சில துணைக் கட்டளைகள் அவற்றின் சொந்த பயன்பாட்டு ஆவணங்களைக் கொண்டுள்ளன, அவை `tldr git subcommand` வழியாக அணுகலாம்.
> மேலும் விவரத்திற்கு: <https://git-scm.com/>.

- Git பதிப்பைச் சரிபார்க்கவும்:

`git --version`

- பொதுவான உதவியைக் காட்டு:

`git --help`

- Git துணைக் கட்டளையில் உதவியைக் காட்டு (`clone`, `add`, `push`, `log` போன்றவை.):

`git help {{துணை_கட்டளை}}`

- ஒரு Git துணைக் கட்டளையை இயக்கவும்:

`git {{துணை_கட்டளை}}`

- தனிப்பயன் களஞ்சிய வேர் பாதையில் Git துணைக் கட்டளையை இயக்கவும்:

`git -C {{பாதை/டு/களஞ்சியம்}} {{துணை_கட்டளை}}`

- கொடுக்கப்பட்ட உள்ளமைவு தொகுப்புடன் Git துணைக் கட்டளையை இயக்கவும்:

`git -c '{{கட்டமைப்பு.சாவி}}={{மதிப்பு}}' {{துணை_கட்டளை}}`