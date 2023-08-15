# Darbs ar Git
1. Mapē git_repos noklonēt https://github.com/hashicorp/terraform projektu
> cd C:\Users\Home\Documents\DevOpsKurss\Tasks\Git_repos\terraform
2. Pārbaudīt kādas izmaiņas tika veiktas iepriekšējās nedēļas laikā. Atrast vismaz divus veidus kā to izdarīt.
> git log --since=2023-07-31 --until=2023-08-06
3. Atrast commit kurus veica autors - “Laura Pacilio”
>  git log --author="Laura Pacilio"
4. Atrast vai Laura ir veikusi commit pagājušā gada septembrī?
> git log --author="Laura Pacilio" --since=2022-09-01 --until=2022-09-30 - **Detalizēti commiti**

> git log --author="Laura Pacilio" --since=2022-09-01 --until=2022-09-30 --oneline --count - **tikai commit IDs un messeges**
5. Vai vakar bija Laurai kāds commit?
> git log --author="Laura Pacilio" --since=yesterday 

# Darbs ar Github 

Mans kursa repo : https://github.com/edgmel/devops-course-23