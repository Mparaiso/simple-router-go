go-tiger tasks
==============



orm

orm will be strongly influenced by doctrine orm
Some go orms to take inspiration from 

- [gorm](http://jinzhu.me/gorm/)
- [gorp](https://github.com/go-gorp/gorp)
- [jet](https://github.com/eaigner/jet)
- [hood](https://github.com/eaigner/hood)
- [sqlx](https://github.com/jmoiron/sqlx)
- [pop](https://godoc.org/github.com/markbates/pop)
- [upper2](https://upper.io/db.v2/)
- [upper1](https://upper.io/db.v1/)
- [sqlboilder](https://github.com/vattle/sqlboiler)
- [beego](https://beego.me/docs/mvc/model/overview.md)
- [xorm](https://github.com/go-xorm/xorm)
- [beedb](https://github.com/astaxie/beedb)
- [reform](https://github.com/go-reform/reform)
- [qbs](https://github.com/coocood/qbs)
- [vivom](https://github.com/oguzbilgic/vivom)
- [spiffy](https://github.com/blendlabs/spiffy)
- [goSQL](https://github.com/quintans/goSQL)
- [dbr](https://github.com/gocraft/dbr)

interesting packages :

- [ql](https://github.com/cznic/ql) a pure go SQL database
 
x = done 

funcs

- [x] add funcs.MakeEvery
- [x] add funcs.MakeSome
- [x] add funcs.MakeFilter
- [ ] add funcs.MakeLastIndexOf
- [x] add funcs.MakeFind
- [ ] add funcs.MakeReverse
- [ ] add funcs.MakeSort
- [x] add funcs.MakeForEach
- [x] add funcs.MakeInclude
- [ ] add funcs.MakeDifference
- [ ] add funcs.MakeUnion
- [ ] add funcs.MakeXor
- [x] add funcs.MakeGroupBy https://lodash.com/docs/4.17.2#groupBy 
- [ ] add funcs.MakePartition https://lodash.com/docs/4.17.2#partition
- [ ] add funcs.MakeShuffle
- [x] add funcs.KeyBy https://lodash.com/docs/4.17.2#keyBy `func(collection []T,keyProvider func(element T)K)map[K]T`
- [x] add funcs.GetKeys
- [x] add funcs.getValues

mongo 

- [x] add branch mongo : complete DocumentManager.resolveAllRelations
- [x] 4eaf29 added support for eager/lazy loading of related relationships
- [x] add support for resolveAllRelations/referenceMany/MappedBy 
- [ ] add support for non-nullable fields
- [ ] add support for inversedBy annotation
- [ ] add support for order in mapping
- [ ] add support for specific criteria in mapping
- [ ] add support for limit in mapping
- [H] fix unity of work , make sure a recursive cascade doesn't lead to a stack overflow
