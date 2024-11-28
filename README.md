### About me

```c++
#include <iostream>
#include <string>

class	Dev
{
	public:

		Dev(void);
		~Dev(void);
		Dev(const Dev &copy);
		Dev	&operator=(const Dev &copy);

		Dev(std::string name, std::string location, std::string school, std::size_t age);

		void	code(void);

	private:

		std::string	_name;
		std::string	_location;
		std::string	_school;
		std::size_t	_age;
};

int	main(void)
{
	Dev	pquline("Pauline", "Paris, France", "École 42", 28);

	pquline.code();
	return (0);
}
```

### Current interests

- 🏠 Home Automation
- 🕵️ Open Source Intelligence (OSINT)
- 🚀 Self-hosting & Deployment
- 🌐 [42LogTime](https://42logtime.fr/)
