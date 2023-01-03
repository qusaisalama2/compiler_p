package LAB;

import java.util.HashSet;
import java.util.Set;

public class SymbolTable {
  private static Set<String> variables;
  private static Set<String> functions;

  static {
    variables = new HashSet<>();
    functions = new HashSet<>();
  }

  public static void addVariable(String variableName) {
    variables.add(variableName);
  }

  public static void addFunction(String functionName) {
    functions.add(functionName);
  }

  public static boolean variableExists(String variableName) {
    return variables.contains(variableName);
  }

  public static boolean functionExists(String functionName) {
    return functions.contains(functionName);
  }
}