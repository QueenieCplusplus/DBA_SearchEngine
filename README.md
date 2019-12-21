# DBA_SearchEngine
搜索引擎的架構

                            Server (Framework)
                            
                            Query Engine (API)
                            
       ACL   < = >   Meta Data    +   Query Statement  (Process Phase)
       
        +
        
       Rule            (Query Plan = Query Tree + DDL + Utility )
       
        +
        
      Cache                 Executor + LLVM
                      
                      
                        
                        
