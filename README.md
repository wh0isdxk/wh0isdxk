    .method public static printHelloWorld()V
    .registers 2
    sget-object v0, Ljava/lang/System;->out:Ljava/io/PrintStream;
    const-string v1, "Hello World ♥"
    invoke-virtual {v0,v1}, Ljava/io/PrintStream;->println(Ljava/lang/String;)V
    return-void
    .end method


