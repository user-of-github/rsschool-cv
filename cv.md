## rsschool-cv
# Slutski Nikita
### Contacts:
* *__Location: Minsk, Belarus__*  
* *__GitHub: [@user-of-github](https://github.com/user-of-github)__*
* *__Discord server nickname: Nikita (@user-of-github)__*  
### About me:  
_Hi ! I am currently a student. I have passion for studying and gaining much cool new experience. Besides studying, also enjoy communicating, playing volleyball and walking_
### Skills:  
* _TypeScript / JavaScript_  
* _React_
* _C++_  
* _and other :)_
### Code examples:  
__*C++ :*__  
```
void RemoveSpaceSymbolsFromString(std::string &source)
    {
        const auto check_if_space_symbol{[](char symbol) -> bool { return Utils::kSpaceSymbols.contains(symbol); }};
        const auto new_end{std::remove_if(std::begin(source), std::end(source), check_if_space_symbol)};
        source.erase(new_end, std::end(source));
        source.shrink_to_fit();
    }
```  
__*TypeScript :*__  
```
export const requestToServer = async (parameters: RequestParameters): Promise<any> => {
    const response: Response = await fetch(parameters.url, {
        method: parameters.method,
        headers: parameters.headers,
        body: parameters.body
    })
    const data = await response.json()
    await parameters.callback(response, data)
}
```
### Education:  
* _**Lyceum BSU** — Informatics & Math_
* _**BSUIR** — Computer Science & Programming Technologies_
### *English:*
_B2+ / Upper Intermediate Plus  
I am regulary attending BSUIR English Speaking Club — a wonderful weekly event_
