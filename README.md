# Student-Information
package s;

public class stdinfo {
	String name="Siyam";
	int id=387;
	String Bloodgroup="O+";
	
	public stdinfo() {
		
	}
	public void setName(String name) {
		this.name = name;
	}
	public String getName() {
		return name;
	}
	public void setId(int id) {
		this.id = id;
	}
	public int getId() {
		return id;
	}
	public void setBloodgroup(String bloodgroup) {
		this.Bloodgroup = Bloodgroup;
	}
	public String getBloodgroup() {
		return Bloodgroup;
	}

}

package s;

public class Main {
	
		public static void main(String[] args) {
			stdinfo x=new stdinfo();
			
			System.out.println("Name of student: " +x.getName());
			System.out.println("Name of student: " +x.getId());
			System.out.println("Name of student: " +x.getBloodgroup());
			
		}

	
		



}
