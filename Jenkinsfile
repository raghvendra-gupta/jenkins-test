pipeline {

    parameters {

 

        string(name: 'CLUSTER_TARGET',
            defaultValue: 'dev',
            description: "Name of the cluster you want to deploy to.")

 

        string(name: 'TOPIC_FILE',
            description: "Path to the file containing the topics.")
    }

 

    environment {

 

        CLUSTER_TARGET = "${params.CLUSTER_TARGET}"
        TOPIC_FILE = "${params.TOPIC_FILE}"

 

    }
}
