import java.util.Stack;
public class AscendingStackValues {
	public static Stack<Integer> ascendStack(Stack<Integer> newSts) {
		Stack<Integer> tmpIntegers = new Stack<Integer>();
		while(!newSts.isEmpty()) {
			int tmp = newSts.pop();
			while(!tmpIntegers.isEmpty() && tmpIntegers.peek()>tmp) {
				newSts.push(tmpIntegers.pop());
			}
			tmpIntegers.push(tmp);
		}
		return tmpIntegers;
	}

	public static void main(String[] args) {
		Stack<Integer> newstack = new Stack<>();
		newstack.push(1000);newstack.push(120);newstack.push(80);newstack.push(10);
		newstack.push(180);
		System.out.print(ascendStack(newstack));
		
	}

}
