### About me

```c
#include <stdlib.h>

typedef struct s_person
{
	char			*name;
	char			*location;
	char			*current_school;
	unsigned int		age;
}				t_person;

int	main(void)
{
	t_person	*pquline;

	pquline = (t_person *)malloc(sizeof(t_person));
	if (pquline != NULL)
	{
		pquline->name = "Pauline";
		pquline->location = "Paris, France";
		pquline->current_school = "École 42";
		pquline->age = 27;
	}
	return (0);
}
```

### Current interests

- 🏠 Home Automation
- 🕵️ Open Source Intelligence (OSINT)
- 🚀 Self-hosting & Deployment
