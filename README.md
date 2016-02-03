# Dapper.SqlMapper
```
class Extension
{
  object Insert<TEntity>(object entity);
  int Update<TEntity>(object entity);
  int Delete<TEntity>(Expression<Func<TEntity, bool>> where);
  IEnumerable<TEntity> Query<TEntity>(Expression<Func<TEntity, bool>> where);
  IEnumerable<TEntity> ToDapper<TEntity>();
}
```
