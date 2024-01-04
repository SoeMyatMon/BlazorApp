# BlazorApp

1)
For EntityFramework,
install NETCORE.SQLSERVER & NETCORE.TOOL

2)
 public class DatabaseContext : DbContext
 {
     public DatabaseContext(DbContextOptions<DatabaseContext> options):base(options)
     {
             
     }
     public DbSet<Person> Person { get; set; }
 }

3)
  "ConnectionStrings": {
    "conn": "data source=.;initial catelog=BlazorDB;integrated security=true,TrustServerCertificate=true"
  }
