# BlazorApp

For EntityFramework,

install NETCORE.SQLSERVER & NETCORE.TOOL

 public class DatabaseContext : DbContext
 {
     public DatabaseContext(DbContextOptions<DatabaseContext> options):base(options)
     {
             
     }
     public DbSet<Person> Person { get; set; }
 }
