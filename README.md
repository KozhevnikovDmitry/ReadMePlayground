# Dapper.SqlMapper
```
class Extension
{
  object Insert<TEntity>(this DbSet<TEntity> source, object entity);
  int Update<TEntity>(this DbSet<TEntity> source, object entity);
  int Delete<TEntity>(this DbSet<TEntity> source, 
                      Expression<Func<TEntity, bool>> where);
  IEnumerable<TEntity> Query<TEntity>(this DbSet<TEntity> source, 
                                      Expression<Func<TEntity, bool>> where);
  IEnumerable<TEntity> ToDapper<TEntity>(this IQueryable<TEntity> source);
}
```
