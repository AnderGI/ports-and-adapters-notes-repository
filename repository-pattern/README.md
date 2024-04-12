# Repository pattern

> [!NOTE]
> Repository vs DAO : Conceptual difference. In DAO, we take into account our existing data ( we have x table we have x_table_dao). The way we conceive our objects and data access is the main difference. Repository has a higher level of abstraction. Repository improves ISP principles. However, both can be complementary.

[![Repository vs DAO - CodelyTv](https://img.youtube.com/vi/QqsH0OgqafA/0.jpg)](http://www.youtube.com/watch?v=QqsH0OgqafA)

> first it is an abstraction of the data layer and second it is a way of centralising the handling of the domain objects.[...] The idea with this pattern is to have a generic abstract way for the app to work with the data layer without being bother with if the implementation is towards a local database or towards an online API. [^1]

[^1]: [Repository Design Pattern](https://medium.com/@pererikbergman/repository-design-pattern-e28c0f3e4a30)
