class DayPipeline {
    List<String> stages = ["breakfast", "workout", "study", "familytime", "play"]
    String output = "my day went well"

    void executeStage(String stage) {
        println "Executing stage: $stage"
    }

    void runPipeline() {
        println "Starting the pipeline..."
        stages.each { stage ->
            executeStage(stage)
        }
        println "Output: $output"
    }
}

// Create and run the pipeline
def pipeline = new DayPipeline()
pipeline.runPipeline()
