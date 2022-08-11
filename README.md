# comandos-entity

get-help entityframework
Scaffold-DbContext -provider Microsoft.EntityFrameworkCore.SqlServer -connection "connstring"


------------------------------------------

Alguns comandos do Entity

Scaffold

dotnet add package Microsoft.EntityFrameworkCore -v 2.0.0

dotnet add package Microsoft.EntityFrameworkCore.Design -v 2.0.0

dotnet add package Microsoft.EntityFrameworkCore.Tools.DotNet -v 2.0.0


dotnet ef dbcontext scaffold "Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=C:\git\agendamento-consulta\Dados\Agendamento.mdf;Integrated Security=True"  Microsoft.EntityFrameworkCore.SqlServer -o Models -f -c DemoDbContext --project Servicos

Scaffold-DbContext "Server=.\;Database=AdventureWorksLT2012;Trusted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Model -Context "AdventureContext" -DataAnnotations

------------------------------------------


Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=C:\Users\Rusley\source\repos\ConsoleApp1\ConsoleApp1\Dados.mdf;Integrated Security=True



dotnet ef dbcontext scaffold "Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=C:\Users\Rusley\source\repos\ConsoleApp1\ConsoleApp1\Dados.mdf;Integrated Security=True" Microsoft.EntityFrameworkCore.SqlServer -o Models -f -c DemoDbContext



dotnet add package Microsoft.EntityFrameworkCore -v 2.0.0

dotnet add package Microsoft.EntityFrameworkCore.Design -v 2.0.0

dotnet add package Microsoft.EntityFrameworkCore.Tools.DotNet -v 2.0.0

dotnet ef dbcontext scaffold "Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=C:\Users\Rusley\source\repos\ConsoleApp1\ConsoleApp1\Dados.mdf;Integrated Security=True" Microsoft.EntityFrameworkCore.SqlServer


Scaffold-DbContext "Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=C:\Users\Rusley\source\repos\ConsoleApp1\ConsoleApp1\Dados.mdf;Integrated Security=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -Context "Contexto"


Scaffold-DbContext "Server=.\;Database=AdventureWorksLT2012;Trusted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Model -Context "AdventureContext" -DataAnnotations

dotnet ef dbcontext scaffold "Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=C:\Users\Rusley\source\repos\ConsoleApp1\ConsoleApp1\Dados.mdf;Integrated Security=True" Microsoft.EntityFrameworkCore.SqlServer


Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=C:\Users\Rusley\source\repos\ConsoleApp1\ConsoleApp1\Dados.mdf;Integrated Security=True
