# quiniela
Este es el codigo realizado en Java
```Java
import java.util.*;

public class Quiniela {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int num=3;
		String n1="",n2="",n3="",n4="",n5="",n6="",n7="",n8="",n9="",n10="",n11="",n12="",n13="",n14="";
		String result;
		
		for (int i = 0; i < num; i++) {
			if(i==0) {
				n1="1";
			}
			if(i==1) {
				n1="x";
			}
			if(i==2) {
				n1="2";
			}
			for (int j = 0; j < num; j++) {
				if(j==0) {
					n2="1";
				}
				if(j==1) {
					n2="x";
				}
				if(j==2) {
					n2="x";
				}
				for (int k = 0; k < num; k++) {
					if(k==0) {
						n3="1";
					}
					if(k==1) {
						n3="x";
					}
					if(k==2) {
						n3="2";
					}
					for (int m = 0; m < num; m++) {
						if(m==0) {
							n4="1";
						}
						if(m==1) {
							n4="x";
						}
						if(m==2) {
							n4="2";
						}
						for (int n = 0; n < num; n++) {
							if(n==0) {
								n5="1";
							}
							if(n==1) {
								n5="x";
							}
							if(n==2) {
								n5="2";							}
							for (int l = 0; l < num; l++) {
								if(l==0) {
									n6="1";
								}
								if(l==1) {
									n6="x";
								}
								if(l==2) {
									n6="2";
								}
								for (int o = 0; o < num; o++) {
									if(o==0) {
										n7="1";
									}
									if(o==1) {
										n7="x";
									}
									if(o==2) {
										n7="2";
									}
									for (int p = 0; p < num; p++) {
										if(p==0) {
											n8="1";
										}
										if(p==1) {
											n8="x";
										}
										if(p==2) {
											n8="2";
										}
										for (int q = 0; q < num; q++) {
											if(q==0) {
												n9="1";
											}
											if(q==1) {
												n9="x";
											}
											if(q==2) {
												n9="2";
											}
											for (int r = 0; r < num; r++) {
												if(r==0) {
													n10="1";
												}
												if(r==1) {
													n10="x";
												}
												if(r==2) {
													n10="2";
												}
												for (int s = 0; s < num; s++) {
													if(s==0) {
														n11="1";
													}
													if(s==1) {
														n11="x";
													}
													if(s==2) {
														n11="2";
													}
													for (int t = 0; t < num; t++) {
														if(t==0) {
															n12="1";
														}
														if(t==1) {
															n12="x";
														}
														if(t==2) {
															n12="2";
														}
														for (int u = 0; u < num; u++) {
															
															for (int w = 0; w < num; w++) {
																if(w==0) {
																	n14="1";
																}
																if(w==1) {
																	n14="x";
																}
																if(w==2) {
																	n14="2";
																}
																
																ArrayList<String> quiniela=new ArrayList<String>();
																
																quiniela.add(n1);
																quiniela.add(n2);
																quiniela.add(n3);
																quiniela.add(n4);
																quiniela.add(n5);
																quiniela.add(n6);
																quiniela.add(n7);
																quiniela.add(n8);
																quiniela.add(n9);
																quiniela.add(n10);
																quiniela.add(n11);
																quiniela.add(n12);
																quiniela.add(n13);
																quiniela.add(n14);
																
																int cont1=0;
																int contX=0;
																int cont2=0;
																for (int cont = 0; cont < 13; cont++) {
																	if(quiniela.get(cont).equals('1')){
																		cont1++;
																	}
																	if(quiniela.get(cont).equals('x')){
																		contX++;
																	}
																	if(quiniela.get(cont).equals('2')){
																		cont2++;
																	}
																}
																if(cont1<5 && cont1>11){
																	System.out.println(n1+" "+n2+" "+n3+" "+n4+" "+n5+" "+n6+" "+n7+" "+n8+" "+n9+" "+n10+" "+n11+" "+n12+" "+n13+" "+n14);
																}
																
																if(contX<2 && contX>6){
																	System.out.println(n1+" "+n2+" "+n3+" "+n4+" "+n5+" "+n6+" "+n7+" "+n8+" "+n9+" "+n10+" "+n11+" "+n12+" "+n13+" "+n14);
																}
																if(cont2<3 && cont2>9){
																	System.out.println(n1+" "+n2+" "+n3+" "+n4+" "+n5+" "+n6+" "+n7+" "+n8+" "+n9+" "+n10+" "+n11+" "+n12+" "+n13+" "+n14);
																}
															}
														}
													}
												}
											}
										}
									}
								}
							}
						}
					}
				}
			}
		}
	}
}
```
