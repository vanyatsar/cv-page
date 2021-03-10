# Ivan Tsar

### Contacts

- **VK:** [ivan_tsar99](https://vk.com/ivan_tsar99)
- **Telegram:** @vanyatsar
- **Discord:** Vanya Tsar#3378
- **LinkedIn:** [ivan-tsar-516000140](https://www.linkedin.com/in/ivan-tsar-516000140/)
- **Gmail:** [ivan.tsar99@gmail.com](mailto:ivan.tsar99@gmail.com)
- **Phone:** +375 (44) 754 835 13

### Summary

> I'm working in Epam as Junior Test Automation Engineer on C#. I want to learn JS, CSS, NodeJS and other technologies that would help me to become a strongly fullstack specialist.

### Skills

- HTML5 / CSS3
- JavaScript, C#
- SQL / MYSQL
- Azure DevOps, Jenkins, Jira
- Selenium, NUnit, MSTest
- Automation Testing in C#
- Git, Github

### Working Experience

- _Job Position:_ Test Automation Engineer
- _Project Roles:_ Automation Engineer
- _Customer:_ Thomson Reuters, Business Information and Media
- _Project:_ TRI-3ECR, - Refactoring of services for Thomson Reuters Elite 3E Product: Core Module, Components, Tools; - Testing, Test Automation
- _Participation:_

  > - Maintain the API and UI test automation framework based on C# .NET and custom Titanium UI framework.
  > - Implement and updated existing automated tests.
  > - Created and updated test cases in Azure DevOps(TFS).
  > - Participated in regular meeting in daily stand-ups, iteration planning and status calls.
  > - Maintain release definitions on CI
  > - Performed test automation code review and refactoring.

- _Team:_ QA team: 11 automation engineer
- _Database:_ Microsoft SQL Server
- _Tools:_ Git, Microsoft DevAzure, Azure DevOps CI, MS Visual Studio 2019, Titanium TAF based on RestSharp and Selenium.
- _Technologies:_ C# .NET

### Education

**BSU - Faculty of Radiophysics and Computer Technologies (Bachelor's degree)**
2016 - 2020 Radiophysicist

**BSU - Faculty of Radiophysics and Computer Technologies (Master's degree)**
2020 - 2022

### English

Intermediate (B1)

### Code examples

C#

```c#
public bool AddAuto(Auto car)
{
    if (cars.Count == 0)
    {
        cars.Add(car);
    }
    else
    {
        foreach (Auto auto in cars)
        {
            if (!car.Equals(auto))
            {
                cars.Add(car);
                return true;
            }
        }
    }
    return false;
}
```
