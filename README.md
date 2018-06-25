PDO Database Library by Riki Mahendra <mahendrariki02@gmail.com>
================================================================

Usage example:

```
public $default     = array(
							        'datasource'    => 'Database/Mysql',
							        'persistent'    => false,
							        'host'          => 'localhost',
							        'login'         => 'root',
							        'password'      => '',
							        'database'      => 'db_test',
							        'prefix'        => '',
							        'encoding'      => 'UTF8',
							        'port'          => '',
						       );
```



include pada file index.php : 

```
require_once 'config/database.php';
```