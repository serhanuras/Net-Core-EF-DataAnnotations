PM> enable-migrations (Enables the migration in your project by creating a Configuration class.)
PM> add-migration MIGRATION_NAME (Creates a new migration class as per specified name with the Up() and Down() methods.)
PM> update-database -verbose (Executes the last migration file created by the Add-Migration command and applies changes to the database schema., 
							  Use the –verbose option to view the SQL statements being applied to the target database.)
PM> PM> update-database -TargetMigration:SchoolDB-v1 (Rollback Migration)