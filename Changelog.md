// top version is work in progres
0.9.3
  - Multiple results support in binary protocol              #27
  - Apply timezone from config to DATETIME values with no tz #15

0.9.2
  - correctly parse NULL result for string and number        #35       0a4ac65ec812f75861dc00c9243921d5d6602914
  - do not pollute global namespace from evaled parser       #11       4b6ddaf0f70150945d0fea804db9106f343a0e51

0.9.1
  - PoolClaster ported from node-mysql                       #34

0.8.21
  - Fix in error message parsing (Noam Wasersprung)          #31       6cc80a67eaa3baac7dd8eee7182c9eb00977e81a
  - return insert/delete header for insert/delete commands   #32       72aa8fe70981d7410a10edb9d7921e5d6ce1d3ca

0.8.20
  - Make packet parser work with 0.11 ondata(buffer) with no start,end 9005fd1
  - Allow to use Date-like objects as date parameters (Amir Livneh)    6138dad0581fd5e2c45e1ce0b999e334db8979cf
0.8.19
  - Multiple results support in text protocol #15                      4812adaf1aa5b1dfa775a6cf0fa3bae54a7827d0
  - Use connection flags from createConnection parameters/url string   9218f055ceeb95ae7205348e06c07b89b799d031
