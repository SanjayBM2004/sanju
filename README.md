

//*public class App 
{
    public static void main( String[] args )
    {
        System.out.println( "Hello World!" );
        
    }
    public long calfact(int no) {
    	if(no<0) {
    		throw new IllegalArgumentException("no ne");
    	}
    	long fact=1;
    	for(int i=1;i<=fact;i++) {
    		fact *=i;
    	}
    return fact;
    }
    
}


public class AppTest 
    extends TestCase
{
   private App app;
    public AppTest( String testName )
    {
        super( testName );
        this.app= new App();
        
    }
    public void testcase0() {
    	assertEquals("fngn ",1,this.app.calfact(0));
    }
    public void testcase1() {
    	assertEquals("fbdfb",1,this.app.calfact(1));
    }
}



mvn archetype:generate -DgroupId=com.in.newp6 -DartifactId=newp6 -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false*//
