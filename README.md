# testkub
ทดสอบ






package testtest;

import java.lang.ArrayIndexOutOfBoundsException;
import java.io.BufferedReader;
import java.io.FileReader;
import java.io.IOException;

public class play {
	public static void main(String[] args) {
		
		BufferedReader in = null;
		try{
			in = new BufferedReader(new FileReader("C:/Users/Queryeiei/workspace/Dev_Test_2016/1.working_time.log"));
			String read = null;
			String n = "/+s";
			while((read = in.readLine()) != null){
				String[] splited = read.split("\\|");
				String[] parts = null;
				
				for(String part : splited){
					System.out.println("______________________");
					System.out.println("Spliter 0 ="+splited[0]);
					System.out.println("Spliter 1 ="+splited[1]);
					System.out.println("Spliter 2 ="+splited[2]);
					System.out.println("Spliter 3 ="+splited[3]);
					System.out.println("Spliter 4 ="+splited[4]);
					System.out.println("______________________");
					//if()
					//{
						
					//}
					break;
				}
				if(splited[0].equals("�.�.��Ǵ� ���ʾ��Ż")){
					System.out.println("______________________");
					System.out.println("Spliter 0 ="+splited[0]);
					System.out.println("Spliter 1 ="+splited[1]);
					System.out.println("Spliter 2 ="+splited[2]);
					System.out.println("Spliter 3 ="+splited[3]);
					System.out.println("Spliter 4 ="+splited[4]);
					System.out.println("______________________");
				}
				
			}
			
		}catch (IOException e){
			System.out.println("ERROR PLEAS TRY AGAIN!!!" + e);
			e.printStackTrace();
		}finally{
			try{
				in.close();
			}catch(Exception e){
				
			}
		}
				}
}



