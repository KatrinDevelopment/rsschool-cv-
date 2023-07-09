# Katrin Sakharova
**Contacts:**
- Location: Moscow, Russia
- Telegram: @Katriyi
- Email: jessup@yandex.ru
- GitHub: KatrinDevelopment

**About Me:**
I have a law degree and worked for many years as a corporate lawyer. One year ago I moved to the IT department and expand my backend and frontend stack.

## Skills
- Python
- Django
- REST API
- Docker
- SQL
- HTML
- JavaScript

### Code Example

    def get_api_answer(
       timestamp: int,
    ) -> Dict[str, Union[List[Dict[str, str]], int]]:
       """Makes a request to API."""
       try:
           response = requests.get(
               ENDPOINT,
               headers=HEADERS,
               params={
                   'from_date': timestamp,
               },
           )
       except requests.exceptions.RequestException as error:
           logger.error(
               EndpointException(),
               exc_info=True,
           )
           raise ConnectionError(error)

## Experience
- **Хpractice**, junior developer (python backend on Django, API, telegram botes)

- **International company Nissan** (rep office Russia, Ukraine, Kazakhstan), lawyer: contracts, verification of car dealers, verification of promotional materials.
- **Ceremonies Staging Agency**, lawyer: legal issues of the Olympic Games opening ceremony in Sochi.

## Education
**University:**
- Russian Academy of Justice, lawyer

**Projects:**
- Students exchange program(USA, Appleton)
- [Jessup moot court Competition(USA, Washington)](http://www.ilsa.org/about-jessup/ "Jessup moot court Competition(USA, Washington)")

## English
Upper-Intermediate (B2)
