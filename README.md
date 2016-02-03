```
class SqlMapper
{
  // IDbConnetion extensions
  
  int Execute(string sql);
  object ExecuteScalar(string sql);
  IEnumerable<T> Query<T>(string sql);
  GridReader QueryMultiple(string sql);
}
```
