# Dapper.SqlMapper
```
class Extension
{
  object Insert<T>(object entity);
  int Update<T>(object entity);
  int Delete<T>(Expression<Func<T, bool>> where);
  IEnumerable<T> Query<T>(Expression<Func<T, bool>> where);
  IEnumerable<T> ToDapper<T>();
}
```
