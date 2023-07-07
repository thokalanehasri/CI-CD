pipeline{
  any stage{
      stages("Build"){
        start()
        }
      stages("Test"){
        start()
      }
      stages("Deploy"){
        start()
        }
      }
    }
