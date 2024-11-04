### About me

```c
#include <stdlib.h>
#include <string.h>

typedef struct s_dev
{
	char			*name;
	char			*location;
	char			*current_school;
	unsigned int		age;
}	t_dev;

void	code(t_dev *dev);

int	main(void)
{
	t_dev	pquline;

	pquline.name = strdup("Pauline");
	pquline.location = strdup("Paris, France");
	pquline.current_school = strdup("École 42");
	pquline.age = 28;
	code(&pquline);
	return (0);
}
```

### Current interests

- 🏠 Home Automation
- 🕵️ Open Source Intelligence (OSINT)
- 🚀 Self-hosting & Deployment
- 🌐 [42LogTime](https://42logtime.fr/)
