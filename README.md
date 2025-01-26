### About me

```c++
#include <iostream>
#include <string>

class Dev
{
private:
    std::string	_name;
    std::string	_school;
    std::string	_location;
public:
    Dev(const std::string &name, const std::string &school, const std::string &location);
    void code(void) const;
};

int main(void)
{
    Dev pquline("Pauline", "École 42", "Paris, France");
    pquline.code();
    return (0);
}
```

### Current interests

- 🔐 Computer Security ([Root Me](https://www.root-me.org/pquline))
- 🕵️ Open Source Intelligence (OSINT)
- 🚀 Self-hosting & Deployment
- 🌐 Web Development ([42LogTime](https://42logtime.fr/))
